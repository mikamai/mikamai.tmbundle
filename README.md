# Mikamai TextMate2 bundle

> The Mikamayer's TextMate2 Toolkit
> –G. Washington

## Commands

### Compile markdown to dev.mikamai.com's HTML

No shortcut for this one, you must use the bundle item selector (<kbd>⌃⌘T</kbd>) and then type `mikamai`
to select it.

![](http://cl.ly/image/0q3S13423Z1Z/Screen%20Shot%202014-04-02%20at%204.04.17%20pm.png)

Remember to [**set your tumblr editing format to HTML**](https://www.tumblr.com/settings/dashboard).


## Installing

```bash
# Textmate2
mkdir -p ~/Library/Application\ Support/Avian/Bundles/
cd ~/Library/Application\ Support/Avian/Bundles/
git clone https://github.com/streeter/mikamai.tmbundle.git

# Then, make sure you've got `redcarpet` and `pygments` installed with your gem library with system's Ruby 1.8:
type rvm &> /dev/null && rvm system    # for RVM
export RBENV_VERSION="system"          # for rbenv
sudo /System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/bin/ruby -S gem install redcarpet -v 2.3.0
sudo /System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/bin/ruby -S gem install pygments.rb
```
