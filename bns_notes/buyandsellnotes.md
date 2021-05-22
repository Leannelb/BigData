## namespace bns_notes
## dotnet commands
### to delete migratons
 dotnet ef database drop -c AppIdentityDbContext -p Infrastructure -s API
### create a new migration

dotnet ef migrations add InitialCreate -p Infrastructure -s API/ -o Data/Migrations -c StoreContext

    I was having troble with my migrations for agesss. couldnt see products or types or brands and it told me it couldnt create the migration because there were 2 contexta. I fixed it by Dropping then Deleting the skinet db as everything was fine with the identity one. Then i created another, specifyting the context.
### 1. drop & remove migrations 
dotnet ef database drop -p Infrastructure -s API/ -c StoreContext

### 2. remove migrations
**from root folder /BasMigration**

dotnet ef migrations remove -p Infrastructure -s API/ -c StoreContext

### 3. create a new migration
dotnet ef migrations add InitialCreate -p Infrastructure -s API/ -o Data/Migrations -c StoreContext


## Error on using subscribe, they have changed the format:
### from:
    saveUserAddress() {
    this.accountService.updateUserAddress(this.checkoutForm.get('addressForm').value)
        .subscribe(() => {
            this.toastr.success('Address saved');
        }, error => {
            this.toastr.error(error.message);
            console.log(error);
        });
    }

### to:
    .subscribe({
        complete: () => { ... }, // completeHandler
        error: () => { ... },    // errorHandler 
        next: () => { ... },     // nextHandler
        someOtherProperty: 42
    });
### so: 
    saveUserAddress() {
    this.accountService.updateUserAddress(this.checkoutForm.get('addressForm').value)
        .subscribe({
            complete: () => {this.toastr.success('Address saved')},
            error: () => {
                this.toastr.error(error.message);
                console.log(error);
            }
        });
    }