XCoreLib
=================================================================
#����
+ ������ǿ�Դ��,����ֹ������ҵĿ��,����Ҫ׷����������.
#���νṹ
+ //developed by cht
	+ `namespace` XCore
		+`class` XmlBase:object Ϊ����<see cref="XDocument"/>���������ṩ����.
		+ `namespace` Component
			+ `enum` ConvertType:int 
			+ `enum` XSerializeOption:int
			+ `class` USettingsBase:XmlBase
				+ `static method` ToElement() as Element;
				+ `static method` ToObject() as object;
				+ `static method` XSerialize();
			+ `class` USettingObject:USettingsBase
		+ `namespace` InnerAnalyser
			+ `interface` IXmlSerializable
				+ `method` Serialize() as XElement;
				+ `method` DeSerialzie(XElement);
+ //developed by qht
	+ no record found!
#����
+ 2018/5/17-2018/6/9
	+ (2018/5/17 1.0.3.0) ���л��ͷ����л��������ݼܹ�����.