# Github-work-in-VScode

It will show you how to use GitHub in VScode. 

## 1. Create a repository and init it

![image](IMG/Create&init.png)

This operation is equivalent to typing in the VSCode terminal:

```shell
git init
git add README
git commit -m 'First commit'
```

## 2. Setting config in VScode terminal

```shell
git config --global user.name "your github name" 
git config --global user.email "your github email"
```

## 3. Clone(Pull) repository
### Clone

* Open VScode in your work folder and use its terminal

```shell
git clone  https://github.com/*****.git
cd "your repository"
```

### Pull

![image](IMG/Pull.png)

This operation is equivalent to typing in the VSCode terminal:

```shell
git pull origin master
```

## 4. Push your change to Github

* When you finish your code edit or do some other changes have been made to the project, you can push your change to Github in this way. 

![image](IMG/Push.png)

This operation is equivalent to typing in the VSCode terminal:

```shell
git push origin master
```

# Then you can during basic operate of Github in VScode. 
