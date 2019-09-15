1. Oleksandr Yehorov
2. Contact Information:
   Tel. +380505624750
   E-Mail sasha_yegorov@ukr.net
   Skype live: sasha_yegorov
   Github: github.com/oleksandr-yehorov
3. About Me:
   * Well-organized
   * Sociable
   * Able to work in a team
   * Flexible
   * Responsible
   * Detail-oriented
   * Able to make decisions quickly
   * Self-confident
   * Ready to learn
4. Skills:
   * Good knowledge of HTML, CSS and JavaScript
   * Basic knowledge of Bootstrap
   * Familiar with React
   * Basic knowledge of OOP
   * Familiar with Git version control
5. Code examples:
    
   '''
   function readData() {
            let inputArray = document.getElementById('inputArray').value.replace(new RegExp('\n', 'g'), '').split(',').map(item => parseInt(item))
            let isValid = true;
            inputArray.forEach(function(elem){
                if (isNaN(elem)){
                    document.getElementById('validationError').innerHTML='Array contains non number element.';
                    isValid = false;
                }
            });
            return isValid ? inputArray : undefined;
        }
    '''
    
    '''
    function CountingSort(A) {
            let Count = [],
                resultArr = [];
            for (var i = 0; i < A.length; i++) Count[ i ] = 0;
            for (i = 0; i < A.length - 1; i++) {
                for (var j = i+1; j < A.length; j++) {
                    if (A[i] < A[j]) Count[j]++;
                        else Count[i]++;
                    }
                }
            for (i = 0; i < A.length; i++) resultArr[Count[i]] = A[i];
            return resultArr;
            }
    '''