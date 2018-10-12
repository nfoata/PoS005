```
ng new shop   # Creation of a new project
ng serve      # Check that the server has been launched

# Create a project on GCP Firebase: My Shop Project
# Copy the links for the connections with environement project

    apiKey: "AIz...",
    authDomain: "my-shop-project-....firebaseapp.com",
    databaseURL: "https://my-shop-project-....firebaseio.com",
    projectId: "my-shop-project-...",
    storageBucket: "my-shop-project-....appspot.com",
    messagingSenderId: "9865..."

rm -rf /tmp/npm*
npm config get registry
npm config set registry http://
npm i --save firebase  # 
npm i --save angularfire2@4.0.0-rc.1


app.module.ts # import { AngularFireModule } from 'angularfire2'
app.module.ts # import { AngularFireDatabaseModule } from 'angularfire2/database'
app.module.ts # import { AngularFireAuthModule } from 'angularfire2/auth'

npm i --save popper.js node-pre-gyp jquery bootstrap
npm i --save @ng-bootstrap/ng-bootstrap
import { NgbModule } from '@ng-bootstrap/ng-bootstrap'
NgbModule.forRoot()


# Site pages and components
ng g c navbar
ng g c home            # Main page
ng g c products        # Catalog of products
ng g c shopping-cart   # Panier
ng g c check-out       # Reglement
ng g c order-sucess    # Commande reussie
ng g c my-orders       # Customer previous orders
ng g c login
ng g c admin/admin-products # Managing products
ng g c admin/admin-orders   # Managing orders

# Routing
import { RouterModule } from @angular/router
RouterModule.forRoot( { path: , component }


```
