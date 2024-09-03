	dat.newData = table.copy(newData)
	return dat
end
-- 清除商店的数据(包括卡包),相当于离开商店清除商店的数据
function ShopData.ClearAllShopData(self)
	self.cpSelect_fcCardData = {} --卡包选择-功能牌
	self.cpSelect_gameCardData = {}--卡包选择-游戏牌
end

-- 更新余额
function ShopData.UpdateBalance(self, newBalance)
