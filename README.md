# last-indonesia-earthquake
This package about the last earthquake from BMKG Indonesia
## HOW IT WORK 
This package will scrape from [BMKG](https://www.bmkg.go.id) to get latest quake happened in indonesia 
This package will use BeautifulSoup4 and Requests to then generate output in the form of Json which is ready to be used in web or mobile applications

## HOW TO USE
```
if __name__ == '__main__':
    print('The main appication')
    result = recentearthquake.extration_data()
    recentearthquake.show_data(result)
```
## AUTHOR 
RIJALUDDIN