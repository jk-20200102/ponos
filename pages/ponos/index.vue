<template>
  <div>
    구분:
    <select name="where" id="where">
      <option value="머리">머리</option>
      <option value="목">목</option>
      <option value="가슴">가슴</option>
      <option value="팔">팔</option>
      <option value="손">손</option>
      <option value="배">배</option>
      <option value="다리">다리</option>
      <option value="발">발</option>
    </select>
  </div>
  <div>
    통증정도:
    <input type="radio" name="pain-intensity" id="pi1">1
    <input type="radio" name="pain-intensity" id="pi2">2
    <input type="radio" name="pain-intensity" id="pi3">3
    <input type="radio" name="pain-intensity" id="pi4">4
    <input type="radio" name="pain-intensity" id="pi5">5
    <input type="radio" name="pain-intensity" id="pi6">6
    <input type="radio" name="pain-intensity" id="pi7">7
    <input type="radio" name="pain-intensity" id="pi8">8
    <input type="radio" name="pain-intensity" id="pi9">9
    <input type="radio" name="pain-intensity" id="pi10">10
  </div>
  <div>
    메모:
    <textarea name="memo" id="memo" cols="30" rows="10"></textarea>
  </div>
</template>