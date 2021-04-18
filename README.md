# HandBrakeCLI-ColabNotebook v1.3

Consider giving this repo a star ⭐ if it helped you.

<center><a href="https://twitter.com/sangramgorai"><img src='https://upload.wikimedia.org/wikipedia/fr/thumb/c/c8/Twitter_Bird.svg/295px-Twitter_Bird.svg.png' height="70" alt="Contact using Twitter"/></a><a href="https://github.com/SKGHD/Handy/"><img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Font_Awesome_5_brands_github.svg/800px-Font_Awesome_5_brands_github.svg.png' height="70" alt="Github"/></a></center>
<img src="https://hitcounter.pythonanywhere.com/count/tag.svg?url=https%3A%2F%2Fgithub.com%2FSKGHD%2FHandy%2F" alt="Hits">
<br><b><h3>Features:</h3></b>
  <li>Mount/Unmount your Cloud drive with rClone.</li>
  <li>Transfer files between your cloud drives with the speed of google's fast servers.</li>
  <li>Convert videos online with the help of HandBrake.</li>
  <li>Batch Convert directories.</li>
  <li> Resume support for Batch conversion jobs. Pick up right after the last successful conversion in Batch Job when your colab notebook restarts or disconnects. </li>
  <li>Get email notification when your task(s) have finished.</li>
  <li>Extract audio from video clips! </li>
  <li>Remove audio from video clips! </li>
  <li>Extract images from video clips! </li>
</ul>

# Usage

Click on the "Open in Colab" button.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SKGHD/Handy/blob/master/HandBrakeCLI_Colab.ipynb)

# Notes

<li> To use email notifications only gmail id can be used and use an app specfic password <a href="https://myaccount.google.com/apppasswords">Google account settings</a> in order for the feature to work. </li> 
<li> Only you and those who can see your screen physically can see your passwords. </li>
<li> Your passwords are stored in a local variable in your Jupyter Notebook and not stored anywhere less. It gets automatically destroyed when Google purges your notebook. </li>
<li> Do not remove processed_db.txt from your current batch directory else it'll process same files again and again each time you restart the notebook!</li>
<br>
<p>Read more about app specific passwords here: <a href="https://support.google.com/accounts/answer/185833?hl=en">Google Account Help</a>

# FAQs

<li>Q> What is rclone? How do I get rclone.conf file?</li>
<li>A> Everything has been answer here in this forum. Please have a read :<a href="https://onehack.us/t/colab-notebook-to-compress-videos-using-handbrake/104456/9?u=skghd">Rclone</a></li>
<li>Q> How to add more flags to the script?</li>
<li>A> Just add them to the Additional_Flags: ______ in below format.</li>
Example: `--bframes '8' rc-lookahead '40' no-rect`
Note: Numbers should be in single quotes.

<li>Q> Where do I ask for help or feature requests?</li>
<li>A> Open a new request or issue here in github. Please don't message me directly.</li>

### Handbrake CLI reference

<p>Read more about CLI commands here: <a href="https://handbrake.fr/docs/en/latest/cli/command-line-reference.html">Handbrake CLI Docs</a>
<br>

## Pull Requests are welcome.
