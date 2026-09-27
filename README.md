# nginx_revers_pow_ddos_protection
Web sites PoW based DDoS protection powered by Nginx revese proxy with NJS
<pre>
  Защита интернет сайтов от DDoS с помощью PoW (proof-of-work) на базе реверс-прокси nginx + njs.
  В каждую HTML страницу бэкэнда nginx добавляет JavaScript, который решает задачу на стороне
  клиента и добавляет выданный на 5 минут токен в cookie. Nginx проверяет токен и если он валиден,
  запрос передается на бэкэнд. В противном случае nginx отвечает страницей - заглушкой.
</pre>
