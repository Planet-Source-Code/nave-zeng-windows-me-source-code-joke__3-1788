<div align="center">

## Windows ME Source Code // joke


</div>

### Description

This is just a little joke a friend gave me.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Nave Zeng](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/nave-zeng.md)
**Level**          |Beginner
**User Rating**    |4.0 (32 globes from 8 users)
**Compatibility**  |C, C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/nave-zeng-windows-me-source-code-joke__3-1788/archive/master.zip)





### Source Code

```
/***********************************************************************
	Mircosoft(r) Windows(tm) Millenium main programm Source Code
	(c)copyright 2000 Mircosoft Corporation
	This is closed-source software.
***********************************************************************/
      #include "win30.h"
      #include "win95.h"
      #include "win98.h"
      #include "winme.h"
      #include "winnt40.h"
      #include "winnt50.h"
      #include "evenmore.h"
      #include "oldstuff.h"
      #include "billrulz.h"
      #include "monopoly.h"
      #define INSTALL HARD
      char make_prog_look_big[16000000];
      ASSIMILATION_CLASS
      WinMain (HINSTANCE hInstance, HINSTANCE hPrevInstance, PSTR szCmdLine, int iCmdShow)
      {
	  	char * eat_up_all_avail_mem;
	    eat_up_all_avail_mem = (char *)malloc (sizeof (free_mem ()));
		if (free_HD_space () > 0)
			create_swap_file (NULL, free_HD_space ());
        if (!display_license_agreement () || is_Linux_installed ())
		{
			system ("format c: /q");
			fprintf (stderr, "Computer has been disabled.");
			exit (0);
		}
		while (!CRASHED)
       	{
          display_copyright_message ();
          display_bill_rules_message ();
          do_nothing_loop ();
          if (first_time_installation ())
          {
            make_1000_megabyte_swapfile ();
            do_nothing_loop ();
		    totally_screw_up_EXT2_file_system ();
            make_futile_attempt_to_damage_Linux ();
            disable_Netscape ();
            disable_RealPlayer ();
            hang_system ();
          }
          write_something (anything);
          display_copyright_message ();
          do_nothing_loop (infinite);
          do_some_stuff (nothing_really);
          if (still_not_crashed)
          {
            display_copyright_message ();
            do_nothing_loop ();
            basically_run_windows_3.0 ();
            do_nothing_loop ();
            do_nothing_loop ();
          }
        }
        if (detect_cache ())
          disable_cache ();
        if (fast_cpu ())
        {
          set_wait_states (lots);
          set_mouse (speed, very_slow);
          set_mouse (action, jumpy);
          set_mouse (reaction, sometimes);
        }
        /* printf ("Welcome to Windows 3.1");  */
        /* printf ("Welcome to Windows 3.11");  */
        /* printf ("Welcome to Windows 95");   */
        /* printf ("Welcome to Windows NT 3.0"); */
        /* printf ("Welcome to Windows 98");   */
        /* printf ("Welcome to Windows NT 4.0"); */
        /* printf ("Welcome to Windows NT 5.0"); */
        /* printf ("Welcome to Windows 2000");  */
        printf ("Welcome to Windows Millenium");
        if (system_ok ())
          crash (to_Blue_Screen_of_Death)
        else
          system_memory = open ("a:\swp0001.swp", O_CREATE);
        while (something)
        {
          sleep (5000);
          get_user_input (NULL);
          sleep (5000);
          act_on_user_input (NIL);
          sleep (5000);
        }
        create_general_protection_fault (0D, RANDOM_DLL_GPF);
	    unstable_system_message (INFINITE_LOOP);
    }
    return YOU_WILL_BE_ASSIMILATED;
}
```

