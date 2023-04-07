<html xmlns=”https://www.w3.org/1999/xhtml”>
<head runat=”server”>
<title></title>
</head>
<body>
<form id=”form1″ runat=”server”>
<div>
<table style=”width: 56%;” align=”center”>
<tr>
<td align=”center” colspan=”2″ width=”90%”>
 
<strong>How to ASP.NET Sending Email</strong></td>
</tr>
<tr>
<td align=”right”>
 From:</td>
<td align=”left”>
<asp:TextBox ID=”txtFrom” runat=”server”></asp:TextBox>
</td>
</tr>
<tr>
<td align=”right”>
 To:</td>
<td align=”left”>
<asp:TextBox ID=”txtTo” runat=”server”></asp:TextBox>
</td>
</tr>
<tr>
<td align=”right”>
Subject</td>
<td align=”left”>
<asp:TextBox ID=”txtSubject” runat=”server”></asp:TextBox>
</td>
</tr>
<tr>
<td align=”right”>
Message</td>
<td align=”left”>
<asp:TextBox ID=”txtMsg” runat=”server” TextMode=”MultiLine”></asp:TextBox>
</td>
</tr>
<tr>
<td align=”center” colspan=”2″>
<asp:Button ID=”btnSend” runat=”server” onclick=”btnSend_Click” Text=”Send” />
</td>
</tr>
</table>
</div>
</form>
</body>
</html>
