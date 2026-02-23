# Connect colab to gitHub


## Config colab
```python
!git config --global user.name "Shojib H. Ruhan"
!git config --global user.email "si.ruhan09@gmail.com"
```

## Not necessary. But easy
```python
token= 'my-secret-token'
username= 'shojibruhan'
repo= 'repo-name'
```

## Clone the repo. Create the in github
```python
!git clone https://{token}@github.com/{username}/{repo}
```

## Change the directory
```python
%cd {repo}
```

## move the file to the folder
> It's more easier if the .ipynb file save in local then upload back and move in.
```python
!mv /content/old-file.ipynb /content/<mainfolder>/<subFolder>
```

## Add & Commit
```python
!git add .
!git commit -m "Added basic notebook"
!git push
```
