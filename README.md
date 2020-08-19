<h1 align="center">Automate Your README to Honour Contributors.</h1>


<p align="center">

<img src="https://raw.githubusercontent.com/8bithemant/Thank-Action/master/heart.svg" alt="heart" height="300px" width="300px">

</p>




 <h2 align="center">Thank You for being a open source contributor, we do appreciate your efforts for making Open Source Awesome.</h2>



#### Initial Setup:

- Create a new Folder `.github` in  your root directory 

- Create a Empty folder ` workflows` inside `.github` folder

- Final :tada:
    - Create a new file `action.yml`



#### The new structure will look like:

`.github/workflows/action.yml`


The final step of initialization is add the following code to 

`action.yml`

```javascript
    on: [push, pull_request]

    jobs:
         contrib-readme-job:
         runs-on: ubuntu-latest
     name: Target README.md
     steps:
         - name: Github Action Contributor
           uses: 8bithemant/Thank-Action@v.03
           env:
             GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```





## Thank You All For Great Help :tada:
<table>
<tr>
                <td align="center">
                    <a href="https://github.com/8bithemant">
                        <img src="https://avatars0.githubusercontent.com/u/62112099?v=4" width="100;" alt="8bithemant"/>
                        <br />
                        <sub><b>Hemant Joshi</b></sub>
                    </a>
                </td></tr>
</table>

## Thank You All For Great Help :tada:
<table>
<tr>
                <td align="center">
                    <a href="https://github.com/8bithemant">
                        <img src="https://avatars0.githubusercontent.com/u/62112099?v=4" width="100;" alt="8bithemant"/>
                        <br />
                        <sub><b>Hemant Joshi</b></sub>
                    </a>
                </td></tr>
</table>

