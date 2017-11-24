# Python2 environment
python main.py -i gfwlist.txt -f surge_gfwlist.conf -l warning --user-rule myrule.txt --surge-proxy-name "proxy_xx1" "proxy_xx2" --surge-proxy "custom,1.2.3.4,80,aes-256-cfb,passwdxxx,https://raw.githubusercontent.com/eastlhu/surge/master/SSEncrypt.module" "custom,1.2.3.4,80,aes-256-cfb,passwdxxx,https://raw.githubusercontent.com/eastlhu/surge/master/SSEncrypt.module"
