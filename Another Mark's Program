Sub inputmarks()
        'FRENCH
        Do
            french = InputBox("Please Enter The Pupils Mark In French")
            If french < 0 Or french > 30 Then
                MsgBox(" Enter a Whole Number Between 1-30")
            End If
        Loop Until french > 0 Or french < 30

        'GERMAN
        Do
            german = InputBox("Please Enter The Pupils Mark In German")
            If german < 0 Or german > 30 Then
                MsgBox(" Enter a Whole Number Between 1-30")
            End If
        Loop Until german > 0 Or german < 30

        'SPANISH
        Do
            spanish = InputBox("Please Enter The Pupils Mark In Spanish")
            If spanish < 0 Or spanish > 30 Then
                MsgBox(" Enter a Whole Number Between 1-30")
            End If
        Loop Until spanish > 0 Or spanish < 30
        'PERFECTBUTDONTWORK WHY?
        displaymarks()
    End Sub
    Sub displaymarks()
        ListBox1.Items.Add("Your French Mark Was " & french)
        ListBox1.Items.Add("Your German Mark Was " & german)
        ListBox1.Items.Add("Your Spanish Mark Was " & spanish)
    End Sub
