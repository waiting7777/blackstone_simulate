<template>
  <div id="app">
    <div class="container">
      <table class="table table-striped table-hover">
        <thead>
          <th>武器／副武</th>
          <th>基礎機率</th>
          <th>失敗加成</th>
          <th>最大層數</th>
          <th>最高機率</th>
          <th>硬衝花石</th>
          <th>硬衝花耐久</th>
        </thead>
        <tbody>
          <tr v-for="item in weapon">
            <td>{{item.level}}</td>
            <td>{{item.base}}%</td>
            <td>{{item.fail}}%</td>
            <td>{{item.maxStack}}</td>
            <td>{{item.maxBase}}%</td>
            <td>{{item.hardStone}}</td>
            <td>{{item.hardDur}}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      weapon: [
        {
          level : 1,
          base : 100,
          fail : 0,
          maxStack : 0,
          maxBase : 0,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 2,
          base : 100,
          fail : 0,
          maxStack : 0,
          maxBase : 0,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 3,
          base : 100,
          fail : 0,
          maxStack : 0,
          maxBase : 0,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 4,
          base : 100,
          fail : 0,
          maxStack : 0,
          maxBase : 0,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 5,
          base : 100,
          fail : 0,
          maxStack : 0,
          maxBase : 0,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 6,
          base : 100,
          fail : 0,
          maxStack : 0,
          maxBase : 0,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 7,
          base : 100,
          fail : 0,
          maxStack : 0,
          maxBase : 0,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 8,
          base : 20,
          fail : 2.5,
          maxStack : 13,
          maxBase : 52.5,
          hardStone : 2,
          hardDur : 10
        },
        {
          level : 9,
          base : 17.5,
          fail : 2,
          maxStack : 14,
          maxBase : 45.5,
          hardStone : 3,
          hardDur : 20
        },
        {
          level : 10,
          base : 15,
          fail : 1.5,
          maxStack : 15,
          maxBase : 37.5,
          hardStone : 5,
          hardDur : 30
        },
        {
          level : 11,
          base : 12.5,
          fail : 1.25,
          maxStack : 16,
          maxBase : 32.5,
          hardStone : 7,
          hardDur : 40
        },
        {
          level : 12,
          base : 10,
          fail : 0.75,
          maxStack : 18,
          maxBase : 23.5,
          hardStone : 11,
          hardDur : 50
        },
        {
          level : 13,
          base : 7.5,
          fail : 0.63,
          maxStack : 20,
          maxBase : 20.1,
          hardStone : 17,
          hardDur : 60
        },
        {
          level : 14,
          base : 5,
          fail : 0.5,
          maxStack : 25,
          maxBase : 17.5,
          hardStone : 23,
          hardDur : 70
        },
        {
          level : 15,
          base : 2.5,
          fail : 0.5,
          maxStack : 25,
          maxBase : 15,
          hardStone : 29,
          hardDur : 100
        },
        {
          level : 16,
          base : 15,
          fail : 1.5,
          maxStack : 25,
          maxBase : 52.5,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 17,
          base : 7.5,
          fail : 0.75,
          maxStack : 35,
          maxBase : 33.75,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 18,
          base : 5,
          fail : 0.5,
          maxStack : 44,
          maxBase : 27,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 19,
          base : 2,
          fail : 0.25,
          maxStack : 90,
          maxBase : 24.5,
          hardStone : 0,
          hardDur : 0
        },
        {
          level : 20,
          base : 1.5,
          fail : 0.25,
          maxStack : 124,
          maxBase : 32.5,
          hardStone : 0,
          hardDur : 0
        },
      ]
    }
  }
}
</script>

<style>

  .container{
    margin-top: 100px;
  }

</style>
