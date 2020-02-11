# The-statement
 
The following 
 
 The way they met
 
    sPath , đường dẫn = tự . _paths_client . find_longest_prefix
     
     
 
        abs_opes_path , tự . bíp 
        
    nếu đường dẫn là Không có : 
    
      # thử đường dẫn 
      
      cho path_name trong itertools . chuỗi ( tự . c . Dynamic_paths , tự . c . base_paths ):
      
        path = tự [ path_name ]
        
        sPath = str ( đường dẫn )
        
        Chuyển đổi một chuỗi đường dẫn tuyệt đối` string_path` thành một đối tượng Đường dẫn thực sự,
    sử dụng đường dẫn cơ sở thích hợp nhất được biết đến.
    
      * abs_opes_path PHẢI là một đường dẫn tuyệt đối
      
      * abs_opes_path PHẢI được root trong một trong những đường dẫn cơ sở được cấu hình đã biết
        đến mô đun đường dẫn.
        
    Phương pháp này sẽ tìm thấy kết quả dài nhất trong tất cả các mục sau:
    
      * đường dẫn tài nguyên mô-đun
      
      * đường dẫn tài nguyên công thức
      
      * đường dẫn repo
      
      * động_path
      
      * cơ sở
      
      ap = tự . abspath ( abs_opes_path )
      
    nếu ap ! = abs_opes_path : order path
    
      nâng cao ValueError ( "đường dẫn không tuyệt đối:% rv% r" % ( abs_opes_path , ap )) depends the same
      
## Turned away
 
 trả về getattr ( tự . _path_mod , tên )
 
    nếu tên trong tự . LỌC LỌC : SAME FACE
    
      trả về chuỗi_filter ( getattr ( tự . _path_mod , tên )) SIGNE
      
    nâng cao
                         ( tự . _path_mod , tên )) # pragma: không che ) ( - )
                         
  def __dir__ ( tự ): # pragma: không che  
 
    # Được sử dụng để trợ giúp show_me_the_modules.py
    
    tự trở về . __dict__ . các khóa () + danh sách (- )
    
### Acting deep
 
 Lớp này mô phỏng giao diện os.path được PathApi trưng ra, tôn trọng
  nền tảng hiện tại theo mô-đun `platform`. Điều này cho phép chúng
  mô phỏng các chức năng đường dẫn theo nền tảng đang được thử nghiệm, thay v
  
   def PathToString_inner ( đường dẫn )
   
    khẳng định isinstance ( path , config_types . Path )
    
    cơ sở_path = đường dẫn . cơ sở . giải quyết ( kiểm tra . kích hoạt )
    
    hậu tố = đường dẫn . nền tảng_ext . nhận ( api . m . nền tảng . )
    
    trả lại api . tham gia ( base_path , * path . Pieces ) + hậu tố  search
    
    
  trả về PathToString_innet
  
def chuỗi
