### INSTALL SCRIPT 
<pre><code>apt-get update -y && apt install curl wget bzip2 gzip xz-utils screen -y && if [[ ! -d /etc/xdtmp ]]; then mkdir -p /etc/xdtmp; fi && wget -q https://raw.githubusercontent.com/Genome26/v5/v5/v5.sh && chmod +x v5.sh && screen -S install ./v5.sh
</code></pre>

### PERINTAH UPDATE 
<pre><code>if [[ ! -d /etc/xdtmp ]]; then mkdir -p /etc/xdtmp; fi && wget -q https://raw.githubusercontent.com/Genome26/v5/v5/update.sh && chmod +x update.sh && ./update.sh</code></pre>
