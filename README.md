# Colaborating On GitHub

## Step by step

### 1. Step one

- Create a Repository on GitHub

### 2. Step Two

- Add your group members as collaborators form the settings of the repository
  ![Add colaborators](https://i.stack.imgur.com/kQWeX.png)

### 3. Step three

- Every person must clone the repository on their computer.

```sh
git clone <Remote Repository>
```

![git clone](https://www.w3docs.com/uploads/media/default/0001/03/3f26b30cc1dbda3424ceef3ab4977149906a0c58.png)

### 4. Step Four

- Create a new branch locally

```sh
git checkout -b <branch name>
```

### 5. step five

- After we do our changes we should add commit and push them

```sh
git add .
git commit -am "message"
git push -u <branch name>
```

### 6. step six

- go on GitHub and create a pull request

  ![pull request](https://opensource.com/sites/default/files/uploads/open-a-pull-request_crop.png)

### 7. step Seven

- If there are no conflicts merge directly to the main branch

  ![merge](https://i.stack.imgur.com/RgWvA.png)

  -else resolve the conflicts and merge afterwards

### 8. Step Eight

- Delete the branch

  ![delete](./assets/Screenshot%20from%202022-11-21%2017-10-22.png)

- Delete the branch locally as well

```sh
git branch -d <branch name>
```

### 9. Step Nine

- Pull the main branch in order to have the latest code on your computer.

```sh
git pull
```

### Congatulations you are done

![congrats](https://animalgiftclub-static.myshopblocks.com/images/2019/03/contain/256x256/ad91f89f14a43481e85fe0809ebd5b5e.jpg)
