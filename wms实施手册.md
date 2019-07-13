# Wms(Base版)实施手册  
----------
# 1.基础资料设置：
## 1.1物料资料设置
### 1.1.1默认仓位
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/1.1.1-1.jpg"  width="1000" hegiht="610" align=center />  
 
### 1.1.2物料辅助属性  
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/1.1.2-1.jpg"  width="1000" hegiht="610" align=center />  
 
### 1.1.3批次管理
#### 1.1.3.1有批次管理
 
有批次管理效果图如下  
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/1.1.3.1-1.jpg"  width="1000" hegiht="610" align=center />    

----------
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/1.1.3.1-2.jpg"  width="1000" hegiht="610" align=center />  
 
#### 1.1.3.2无批次管理  
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/1.1.3.2-1.jpg"  width="1000" hegiht="610" align=center />    

----------
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/1.1.3.2-2.jpg"  width="1000" hegiht="610" align=center />  
 
# 2仓库 
## 2.1仓库设置
### 2.1.1 仓库的分类
仓库的分类设置的物控才可被通知单视为可用库存，纳入分配
 
# 3参数设置（见附件）
 

# 10  生产自制品

## 10.1接到订单或计划生产
### 10.1.1订单：
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.1.1-1.jpg"  width="1000" hegiht="610" align=center />    


### 10.1.2下发制令：
需要制作一个全自动电饭煲（160002），其中包括三种原材料和一个半成品
    
 
其中的半成品（没有库存）需要另外再制作：
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.1.2-1.jpg"  width="1000" hegiht="610" align=center /> 
电饭煲主体（30001）：需要两个原材料和一个半成品（有库存）
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.1.2-2.jpg"  width="1000" hegiht="610" align=center /> 
 
## 10.2供应商发出采购订单，采购原材料
  <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.2-1.jpg"  width="1000" hegiht="610" align=center /> 
  
----------
 <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.2-2.jpg"  width="1000" hegiht="610" align=center /> 
### 10.2.1供应商或客户打标签，贴外箱：原单为订单或通知单
  <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.2.1-1.jpg"  width="1000" hegiht="610" align=center /> 

### 10.2.2 仓库扫码入库（移动端）
 
参数：入库流程为入仓-上架
  <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.2.2-1.jpg"  width="1000" hegiht="610" align=center /> 
### 10.2.3完成入库后，可在 中查看
 
可在即时库存表查询刚入库的物料 
   <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.2.3-1.jpg"  width="1000" hegiht="610" align=center /> 
## 10.3 半成品制作
### 10.3.1发起领料通知单，并打单  
  <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.3.1-1.jpg"  width="1000" hegiht="610" align=center /> 
   <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.3.1-2.jpg"  width="1000" hegiht="610" align=center /> 
  


### 10.3.2车间领料（在移动端操作，操作详情可在操作手册中查看） ：
扫箱外二维码以及板位二维码领料出库
  <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.3.2-1.jpg"  width="1000" hegiht="610" align=center /> 
   <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.3.2-2.jpg"  width="1000" hegiht="610" align=center /> 
  
## 10.4 （半）成品完成后，发起自制入库通知
饭煲主体（半成品）
  <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.4-1.jpg"  width="1000" hegiht="610" align=center /> 
  
饭煲（成品）
   <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.4-2.jpg"  width="1000" hegiht="610" align=center /> 
### 10.4.1扫通知单号，打标签贴箱入库
   <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.4.1-1.jpg"  width="1000" hegiht="610" align=center /> 
### 10.4.2 移动端入库
此处直接上架 ，扫外箱二维码或通知单
   <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.4.2-1.jpg"  width="1000" hegiht="610" align=center /> 
      <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.4.2-2.jpg"  width="1000" hegiht="610" align=center /> 
   
## 10.5 销售出库
### 10.5.1发起销售通知单并打单    
<img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.5.1-1.jpg"  width="1000" hegiht="610" align=center />   
   <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.5.1-2.jpg"  width="1000" hegiht="610" align=center /> 
 
  
 
### 10.5.2去到分配的库位扫外箱码（移动端（详情可查看操作手册）），出库交予承运商
   <img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.5.2-1.jpg"  width="1000" hegiht="610" align=center /> 
 
### 10.5.3生成销售出库单,减去库存
<img src="https://raw.githubusercontent.com/kukukuma/IEWAY/master/wms%E5%AE%9E%E6%96%BD%E6%89%8B%E5%86%8C%E5%9B%BE%E7%89%87/10.5.3-1.jpg"  width="1000" hegiht="610" align=center /> 
 
