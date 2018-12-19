## PHP DDNS Scripts

#### 01.准备 先安装php

    https://github.com/ssrpanel/SSRPanel/wiki/%E7%BC%96%E8%AF%91%E5%AE%89%E8%A3%85PHP7.1.21%E7%8E%AF%E5%A2%83%EF%BC%88CentOS%EF%BC%89

#### 02.权限

    chown -R www:www /root/ddns_namesilo.php

    chmod a+x /root/ddns_namesilo.php
    
#### 03.定时任务

    crontab -e   */10 * * * * php /root/ddns_namesilo.php
    
#### 04.收工  

