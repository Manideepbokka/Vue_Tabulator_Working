<template>
  <div class="hello">
    <vue-tabulator v-model="dados" :options="options" />
  </div>
</template>

<script>
import Vue from "vue";
import vueTabulator from "vue-tabulator";

Vue.use(vueTabulator, { name: "vue-tabulator" });

export default {
  name: "HelloWorld",
  data() {
    return {
      dados: [
        {
          name: "test1",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test2",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test3",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test4",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test5",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test6",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test7",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test8",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test9",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test10",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test11",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test12",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test13",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test14",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test15",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test16",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test17",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test18",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test19",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test20",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test21",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test22",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test23",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test24",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test25",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test26",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test27",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test28",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test29",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test30",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test31",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test32",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test33",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test34",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test35",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test36",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test37",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test38",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test39",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test40",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test41",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test42",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test43",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test44",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test45",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test46",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test47",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test48",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test49",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test50",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test51",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test52",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test53",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test54",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test55",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
        {
          name: "test56",
          age: 15,
          value1: "12312312312",
          value2: "12312312312",
          value3: "12312312312",
          value4: "12312312312",
          value5: "12312312312",
          value6: "12312312312",
          value7: "12312312312",
          value8: "12312312312",
          value9: "12312312312",
          value10: "12312312312",
        },
      ],
      options: {
        selectable: 1,
        columns: [
          {
            title: "개인 정보",
            frozen: true,
            columns: [
              {
                title: "Name",
                field: "name",
                sorter: "string",
                width: 200,
              },
              {
                title: "age",
                field: "age",
                sorter: "string",
                width: 200,
              },
            ],
          },
          {
            title: "Value",
            columns: [
              {
                title: "Value1",
                field: "value1",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value2",
                field: "value2",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value3",
                field: "value3",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value4",
                field: "value5",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value5",
                field: "value5",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value6",
                field: "value6",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value7",
                field: "value7",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value8",
                field: "value8",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value9",
                field: "value9",
                sorter: "string",
                width: 200,
              },
              {
                title: "Value10",
                field: "value10",
                sorter: "string",
                width: 200,
              },
            ],
          },
        ],
      },
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.tabulator {
  height: 400px;
}
.tabulator-tableHolder::-webkit-scrollbar {
  -webkit-appearance: none;
  width: 6px;
  height: 6px;
}
.tabulator-tableHolder::-webkit-scrollbar-thumb {
  border-radius: 4px;
  background-color: #C4C4C4;
}
</style>
