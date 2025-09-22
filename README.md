การพยากรณ์ราคาน้ำมันโดยใช้วิธีการพยากรณ์แบบง่ายเช่น Moving Average และ Naive Forecast สำหรับพยากรณ์ราคาน้ำมันที่ประเทศเกาหลีใต้ในปี 2000 ถึงปี 2025

## 1.ฟังก์ชัน

    1.1 AVERAGE() : AVERAGE(Oil_Price_Dataset[Vehicle diesel])

    1.2 MEDIAN() : MEDIAN(Oil_Price_Dataset[Kerosene])

    1.3 VLOOKUP() : VLOOKUP(I43,Oil_Price_Dataset,3,0)

    1.4 IF() : IF(D2=1,"January",
                    IF(D2=2,"February",
                    IF(D2=3,"March",
                    IF(D2=4,"April",
                    IF(D2=5,"May",
                    IF(D2=6,"June",
                    IF(D2=7,"July",
                    IF(D2=8,"August",
                    IF(D2=9,"September",
                    IF(D2=10,"October",
                    IF(D2=11,"November",
                    IF(D2=12,"December"))))))))))))

## 2.Data Visualization

    กราฟ

    

## 3.บรรณานุกรม

    พิภพ ลลิตาภรณ์. (2553). ระบบการวางแผนและควบคุมการผลิต (ฉบับปรับปรุง).(พิมพ์ครั้งที่ 15).	ebook.lib.ku.ac.th/ebook27/ebook/2014RG0100/

    Microsoft. (2025). VLOOKUP function. https://support.microsoft.com/en-us/office/vlookup-function-0bbc8083-26fe-4963-8ab8-93a18ad188a1

    Microsoft. (2025). Split text into different columns with the Convert Text to Columns Wizard. https://support.microsoft.com/en-us/office/split-text-into-different-columns-with-the-convert-text-to-columns-wizard-30b14928-5550-41f5-97ca-7a3e9c363ed7

    Korean Statistical Information Service. (2025). Price at Gas Station by Type of Product. 																						https://kosis.kr/statHtml/statHtml.do?sso=ok&returnurl=https%3A%2F%2Fkosis.kr%3A443%2FstatHtml%2FstatHtml.do%3Flist_id%3DP2_5%26obj_var_id%3D%26seqNo%3D%26tblId%3DTX_31802_A000%26vw_cd%3DMT_ETITLE%26language%3Den%26orgId%3D318%26path%3D%252Feng%252FstatisticsList%252FstatisticsListIndex.do%26conn_path%3DMT_ETITLE%26itm_id%3D%26lang_mode%3Den%26scrId%3D%26

    Microsoft. (2025). IF function. https://support.microsoft.com/en-us/office/if-function-69aed7c9-4e8a-4755-a9bc-aa8bbff73be2

