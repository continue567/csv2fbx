# csv2fbx
convert csv data model file to fbx model of renderdoc 

just use FBXsdk 2020.1 vs2017 version,use this exe like
ConvertCSV2FBX.exe  xxxx.csv 
output file will in the same folder like xxxx.csv

Notice:
only support x64 compile version and you should config the include and lib directory of the fbxsdk from autodesk

you need to change the string name in your code according to your first row of data created from Renderdoc (at the same time you need to download fbxsdk https://www.autodesk.com/developer-network/platform-technologies/fbx-sdk-2020-0 chose vs2017 version)
or you can change the first row of csvdata responding to vertex attribute name of source code







