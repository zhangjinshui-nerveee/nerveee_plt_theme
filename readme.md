This repo provides a python matplotlib theme that features simple color, thin linewidths, and clear presentation.

# How to use
Clone this repo or simply download the nerveee.mplstyle file. 

Personally, I suggest using a consisent plot style across all (or most) of your plotting. So put it under the directory of 
`~/.config/matplotlib/stylelib`

In your python program, before plotting command: 
`plt.style.use("nerveee")`

This will save you time to specify the line colors, linewidth, or axis linewidth everytime. 

This works well with curve plots so far.

Or if you have internet, simply
`plt.style.use("https://raw.githubusercontent.com/zhangjinshui-nerveee/nerveee_plt_theme/refs/heads/main/nerveee.mplstyle")`

# Roadmap:
- [ ] barplot
- [ ] scatter plot
