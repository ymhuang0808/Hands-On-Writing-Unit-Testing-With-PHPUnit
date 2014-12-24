Hands-On-Writing-Unit-Testing-With-PHPUnit
==================

## Branch: start 

### 目錄結構
* src - 程式
* tests - 測試程式
* vendor - Composer 套件

**更多說明請閱讀 [wiki](https://github.com/ymhuang0808/Hands-On-Writing-Unit-Testing-With-PHPUnit/wiki)**

### 12/24 Exception Demo 測試失敗說明
當時 Test Exceptions 的 annotation 寫錯，導致測試失敗，應該為
```
/**
 * @expectedException \PHPUnitEventDemo\EventException
 * @expectedExceptionMessage Duplicated reservation
 * @expectedExceptionCode 1
 */
```

