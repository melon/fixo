# fixo

A bash-based script for making your Github Contributions panel looks productive.

Before
![before](https://raw.githubusercontent.com/melon/fixo/master/contri-before.png)

After
![after](https://raw.githubusercontent.com/melon/fixo/master/contri-after.png)


## Usage

1. prerequisites
2. clone this repository
3. configure your script
4. run script
5. push your repository

### Prerequisites

You first need to make sure the following commands are available

`date`, `seq`, `head`, `sed`, `bc`

### Clone this repository

```
git clone https://github.com/melon/fixo.git
```

### Configuration

Edit the script `decorator`, and replace `YOURNAME` and `YOUREMAIL` with your own name and email. Make sure that the email you replace with is your **primary Github email address**, or the **private email address** you have told Github to use(more about private email address please refer [this link](https://help.github.com/articles/keeping-your-email-address-private/) ), so that your commits could take effect to reflect commits time on the Contributions panel.

### Run Script

```
./decorator
```
After running this command, your brand new repository will be generated.

### Push your repository to Github

Create a new repository on your Github Account, and then do as the Quick setup told you to.

Go to view your Github profile, then you will find that your Contributions panel is well decorated now.

## Undecorate

This scipt is with almost no side effects. If you don't want your Contributions board to look "full of commits", you can just **delete your repository** you've created that is used just for decorating your Contributions panel.

## License

fixo is released under the [MIT License](http://opensource.org/licenses/MIT).
