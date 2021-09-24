# Earthbound Misfit

This is my attempt at learning [Hugo](https://gohugo.io). 

> **Tongue tied and twisted, just an earthbound misfit, I** - Pink Floyd, Learning to Fly. 

## My Goals with this theme

1. It should look nice, I know this is a subjective thing, so you can judge me if you like.  
1. Be responsive, so it should look good and function whether you're viewing this on a phone, or a desktop/laptop.
1. Be SEO friendly. The output should get a 100 on [Lighthouse](https://developers.google.com/web/tools/lighthouse) reports for SEO. 
1. The final output should also score highly on [Core Web Vitals](https://support.google.com/webmasters/answer/9205520?hl=en)
1. Have a layout for a gallery/portfolio that can be used easily. 


## Inspiration

The design/layout inspiration is from the Starter template that comes with [Bootstrap Examples](https://getbootstrap.com/docs/5.1/examples/starter-template/)

The theme functionality/configuration ideas came from

1. [Vitae Theme](https://github.com/dataCobra/hugo-vitae)
1. [Hugo Documentation](https://gohugo.io/variables/page/#pages)
1. This site uses [Feather icons](https://feathericons.com/) .. I'm not sure why I picked these over font-awesome.. I had never heard of these until a few weeks ago.. font-awesome is probably cached in everyone's browser so those may actually be faster. 

## Features 

### Plausible Analytics 

The theme supports Plausible Analytics, if you're curious why I chose and recommend simple analytics you should read this post by David Mytton [Picking Privacy first analytics](https://blog.console.dev/picking-privacy-first-analytics/). 

To enable it all you need to do is add the following to your config.toml
```toml
[params.toml]
    enabled = true
    domain = 'yourdomain.com'
```

The theme will automatically setup the outbound-link JS. 

If you want some advanced functionality with Plausible analytics, I recommend you use the [Plausible Hugo Component/Module](https://github.com/divinerites/plausible-hugo) 

### Favicons

Favicons can be enabled by setting your params in the config file. 

```toml
[params]
    ... # other stuff
    favicons = true
```

If you have your own favicons, make sure they follow the naming convention as specified, and put them in your static folder. Otherwise it'll use the favicons for the theme. 

### Site Verification 

**Google:** Just add the following line to your configuration file. 

```toml
[params.google]
siteVerification = "YOUR-GOOGLE-SITE-VERIFICATION-CODE"

```

## Demo 

A demo of this site will be available at https://atestpage.com 
