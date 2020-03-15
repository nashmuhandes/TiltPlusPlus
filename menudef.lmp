AddOptionMenu "OptionsMenu"
{
	StaticText ""
	StaticText "Tilt++ v1.65"
	Submenu "$OPTMNU_TILTPLUSPLUS", "TiltPlusPlusMenu"
}

OptionMenu "TiltPlusPlusMenu"
{
	Class "TiltPlusPlusMenu"
	Title "$TILTPLUSPLUSMNU_TITLE"
	Position -32

	StaticText ""
	StaticText "$TILTPLUSPLUSMNU_STRAFETILT_TITLE", 1

	TiltPlusPlusOption "$TILTPLUSPLUSMNU_ENABLED",					"$TILTPLUSPLUSMNU_HELPTEXT_STRAFETILT",				"sv_strafetilt", "YesNo"
	TiltPlusPlusOption "$TILTPLUSPLUSMNU_INVERT",					"$TILTPLUSPLUSMNU_HELPTEXT_STRAFETILT_INVERT",		"sv_strafetiltinvert", "YesNo"
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_SPEED",					"$TILTPLUSPLUSMNU_HELPTEXT_STRAFETILT_SPEED",		"sv_strafetiltspeed", 0.1, 2.0, 0.01, 2
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_ANGLE",					"$TILTPLUSPLUSMNU_HELPTEXT_STRAFETILT_ANGLE",		"sv_strafetiltangle", 0.1, 1.0, 0.01, 2

	StaticText ""
	StaticText "$TILTPLUSPLUSMNU_MOVETILT_TITLE", 1

	TiltPlusPlusOption "$TILTPLUSPLUSMNU_ENABLED",					"$TILTPLUSPLUSMNU_HELPTEXT_MOVETILT",				"sv_movetilt", "YesNo"
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_SPEED",					"$TILTPLUSPLUSMNU_HELPTEXT_MOVETILT_SPEED",			"sv_movetiltspeed", 0.1, 20.0, 0.1, 2
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_ANGLE",					"$TILTPLUSPLUSMNU_HELPTEXT_MOVETILT_ANGLE",			"sv_movetiltangle", 0.01, 0.10, 0.01, 2
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_SCALAR",					"$TILTPLUSPLUSMNU_HELPTEXT_MOVETILT_SCALAR",		"sv_movetiltscalar", 0.0, 1.0, 0.1

	StaticText ""
	StaticText "$TILTPLUSPLUSMNU_TURNTILT_TITLE", 1

	TiltPlusPlusOption "$TILTPLUSPLUSMNU_ENABLED",					"$TILTPLUSPLUSMNU_HELPTEXT_TURNTILT",				"sv_turntilt", "YesNo"
	TiltPlusPlusOption "$TILTPLUSPLUSMNU_INVERT",					"$TILTPLUSPLUSMNU_HELPTEXT_TURNTILT_INVERT",		"sv_turntiltinvert", "YesNo"
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_SCALAR",					"$TILTPLUSPLUSMNU_HELPTEXT_TURNTILT_SCALAR",		"sv_turntiltscalar", 0.0, 20.0, 0.1

	StaticText ""
	StaticText "$TILTPLUSPLUSMNU_UNDERWATERTILT_TITLE", 1
	TiltPlusPlusOption "$TILTPLUSPLUSMNU_ENABLED",					"$TILTPLUSPLUSMNU_HELPTEXT_UNDERWATERTILT",			"sv_underwatertilt", "YesNo"
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_SPEED",					"$TILTPLUSPLUSMNU_HELPTEXT_UNDERWATERTILT_SPEED",	"sv_underwatertiltspeed", 0.1, 20.0, 0.1, 2
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_ANGLE",					"$TILTPLUSPLUSMNU_HELPTEXT_UNDERWATERTILT_ANGLE",	"sv_underwatertiltangle", 0.01, 0.5, 0.01, 2
	TiltPlusPlusSlider "$TILTPLUSPLUSMNU_SCALAR",					"$TILTPLUSPLUSMNU_HELPTEXT_UNDERWATERTILT_SCALAR",	"sv_underwatertiltscalar", 0.0, 1.0, 0.1

	StaticText ""
	StaticText "$TILTPLUSPLUSMNU_DEATHTILT_TITLE", 1
	TiltPlusPlusOption "$TILTPLUSPLUSMNU_ENABLED",					"$TILTPLUSPLUSMNU_HELPTEXT_DEATHTILT",				"sv_deathtilt", "YesNo"
}
