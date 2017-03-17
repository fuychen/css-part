# 固定table的td宽度  
  在第一行th宽度已经固定，第二行td的宽度固定或者不固定的情况下，table设置table-layout:fixed;不好用，表格列宽度不会被固定，依旧自适应。 
  在第一行th宽度已经固定，第二行td不设宽度，table不设置table-layout 的情况下，给th/td加上word-break: break-all; 表格的列宽度固定。
