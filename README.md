# luck-draw
抽奖小程序

通过form表单设定奖品初始值并且存入localstorage；

将所有的奖品根据设定的数量排列到一个数组中，再通过Math.random()方法随机获取抽取到的数量，当然数量越多的奖品被抽中的概率越高

将抽取到的奖品数量在localstorage中的数量相应-1，并且更新对应奖品的localstorage值

再通过一个run方法获取到抽中的奖品在页面上的位置，通过一定的动效展示出来选中的过程









