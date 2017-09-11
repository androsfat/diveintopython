# Working on "Dive Into Python" by Mark Pilgrim

Programs and examples from the online book at [Dive into Python](http://www.diveintopython.net/)  

Using Python 2.7.9  

## For auto complete in shell


```python
import rlcompleter, readline  
readline.parse_and_bind('tab:complete')
```

For Debian  


```bash
echo "export PYTHONSTARTUP=~/.pythonrc" >> ~/.bashrc
```
