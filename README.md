12306_captcha

TODO:���ֺ�ͼƬ�������֤��ѧϰandel��

����

��װ: python�µ�ͼƬ�����PIL

��װ OCR��google ��pytesseract

�ٶȷ�������http://stu.baidu.com/n/image?fr=html5&needRawImageUrl=true&id=WU_FILE_0&name=233.png&type=image%2Fpng&lastModifiedDate=Mon+Mar+16+2015+20%3A49%3A11+GMT%2B0800+(CST)&size=

����
'''
urllib2.Request(url + str(len("ͼƬ")), "ͼƬ", {'Content-Type':'image/png', 'User-Agent':UA})
'''
�ٶ�ʶ��12306��������С�ߴ��ͼƬʶ��100px���µģ�ʹ��ImageMagick�Ŵ�ߴ硣 ��ͼ�ͷŴ�ͼƬ����Ҫ��װһ��ImageMagick��ȷ�����������д��convert���
'''
//�Ŵ�ͼƬ�ߴ� 
def resizeImg() 
{ 
	arrargs = ["-resize", "440", "./test.jpg", "./new_test.jpg"]; 
	command = "convert"+ arrargs[0] + arrargs[1]+arrargs[2]+arrargs[3] os.system(command) 
}
'''