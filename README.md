# ember-template-recast-test
Sample repo for reproducting some bugs with ember-template-recast

Run :
```sh
$ node index.js
```

Expected output
`<SiteHeader @user={{this.user}} class={{if this.user.isAdmin admin}}></SiteHeader>`

Actual output
`<SiteHeader></SiteHeader>`
