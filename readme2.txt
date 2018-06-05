steps
1) ng new example-ng6-lib-app
2) cd example-ng6-lib-app
3) ng generate library example-ng6-lib --prefix=enl
4) ng build --prod example-ng6-lib
5) import lib component in app 
  import { ExampleNg6LibModule } from 'example-ng6-lib';
6) ng serve


Links 
https://blog.angularindepth.com/creating-a-library-in-angular-6-87799552e7e5
https://medium.com/@tomsu/how-to-build-a-library-for-angular-apps-4f9b38b0ed11
