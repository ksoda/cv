# Curriculum Vitae

## Preview

```sh
hugo server
```

## Deploy

<https://gohugo.io/hosting-and-deployment/hosting-on-github/#github-user-or-organization-pages>

```sh
deploy.sh
```

## Build PDF

<https://www.npmjs.com/package/html-pdf>

## Load avatar

```sh
curl -o themes/hugo-devresume-theme/static/assets/images/avatar.png https://www.gravatar.com/avatar/$(echo -n 'name@example.test' |md5sum |head -c32)
```
