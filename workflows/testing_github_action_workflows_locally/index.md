## Testing Workflows

> this method is if you want to avoid having to many commit in your branch workflow it will create a docker container where you can simulate your workflow for free locally before commiting to the remote (this applies to all application that uses github action workflows)

> NOTE: for MAC Users only


```
brew install act
```

> find out the available jobs in acts
```
act --list 
```
> you should see something like this 
![Worfklow image ](./1.png)

> once you see there are jobs then you can test and execute that workflow
```
act -j test
```
> it should display something like this when job is done
![Worfklow image2](./2.png)
