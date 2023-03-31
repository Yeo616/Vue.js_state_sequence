<template>
  <div>
    <h1>정보 입력 페이지</h1>
    <form>
      <div id="inputInfoDiv">
        정보입력하여 DB에 등록 :
        <input type="text" id="infoInput" placeholder="Enter Info" />
        <button id="submitInfo">등록</button>
      </div>
    </form>

    <div id="progressInfo" class="progress">progressing</div>

    <p id="infoOutput"></p>

    <div id="buttonDiv">
      <button id="deleteBtn" type="submit" style="color: tomato">
        데이터 삭제하기
      </button>
    </div>
    <br />
    <div>
      <a href="index.html" target="_self">메인페이지로 이동 </a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.progress {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color: black;
  color: white;
  font-size: 16px;
  border: none;
  outline: none;

  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* cursor: pointer; */
  margin: 10px;
}
</style>
