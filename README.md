# PHPAnonymousFunction
PHP Anonymous Function

```PHP
<?php 
 
 function phpRun($fetch) {
  
  $res = $_GET[$fetch]?? [];
  
   $sb_searchResult = new class( $res ) {
     
     private $wp_sresult;
     
     public function __construct( $res ) {
		 
       $this->wp_sresult = $res; 
       // func run
       do();
    } 
    
    private function do() {
     
      strtoupper($this->wp_sresult);
     
    }
  }
  
} 

```

?>
