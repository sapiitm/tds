1. I have used google colab for this project. Had to use three api to get the required data.
   
    https://api.github.com/search/users --> To get the list of users from Bangalore and follower over 100
   
    https://api.github.com/users/  --> To get the details from each user
   
    https://api.github.com/users/{user}/repos? -->to get the repo details
  
3. From bio column the top most 10 used words after removing stopwords are :
   
[('develop', 158),
 ('engin', 117),
 ('nan', 92),
 ('softw', 77),
 ('stack', 50),
 ('learn', 47),
 ('web', 45),
 ('ful', 44),
 ('build', 40),
 ('dat', 39)]
   
5. Goal is to find out if user with hireable worked more on repos in weekends than others
   
   Find out fraction of repos where user hireable = True is created more on weekends than hireable = False
