# Skype for Business channel for Rasa

### This is a custom Rasa channel based on my python-ucwa scripts https://github.com/dadecoza/python-ucwa-bot .


* Usage:
> rasa_s4b_channel.py -d &lt;skype for business discovery url&gt; -u &lt;username&gt; -p &lt;password&gt; -c %lt;rasa core base url&gt; -t &lt;rasa core authentication token&gt

* Example:
 ```console
python3 rasa_s4b_channel.py \
-d "https://lyncdiscoverinternal.company.com/" \
-u "domain\\username" \
-p "secret" \
-c "http://rasa_core.company.com:5005"
```

