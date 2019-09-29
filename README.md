# hugo   

## quick start
https://gohugo.io/getting-started/quick-start/       



##  Host on GitHub
https://gohugo.io/hosting-and-deployment/hosting-on-github/    


#  in action


```
hugo new site  guide
```


```
cd guide
```


```
git init
```


```
git submodule add https://github.com/matcornic/hugo-theme-learn.git themes/hugo-theme-learn
```




```
cp  -rf themes/hugo-theme-learn/exampleSite/*  ./

```




![original](_image/original.jpg)


![afterChange](_image/afterChange.jpg)








```
#!/bin/bash
hugo new site  knative.guide
cd knative.guide
git init
git submodule add https://github.com/matcornic/hugo-theme-learn.git themes/hugo-theme-learn
cp -rf  themes/hugo-theme-learn/*   ./
```



