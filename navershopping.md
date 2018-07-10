url = 'https://search.shopping.naver.com/search/all.nhn?origQuery=%EC%97%90%EC%96%B4%EC%BB%A8&pagingIndex=1&pagingSize=40&viewType=list&sort=rel&cat_id=50002522&minPrice=20000&maxPrice=999000000&frm=NVSHPRC&query=%EC%97%90%EC%96%B4%EC%BB%A8'
r = requests.get(url)
r.text
r = requests.get(url)
soup = BeautifulSoup(r.text, 'html.parser')
soup
goods = soup.select('ul.goods_list li div.info a.tit')
goods
print("네이버 쇼핑 에어컨 순위")
for prod in goods:
    print(prod['title'])
print("=네이버 쇼핑 에어컨 순위=")
num=0
for prod in goods:
    num=num+1
    #num +=1
    print(num, prod['title'])
for seq, prod in enumerate(goods, start=1):
    print(seq, prod['title'])
