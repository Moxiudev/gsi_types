GSI Naming: 
(Last Updated on: 20241230)

Format:
<ARCH>_xyZ

Components:
1. <ARCH> (Architecture)
   - arm   : ARM 32-bit
   - a64   : ARM 32-bit with 64-bit binder
   - arm64 : ARM 64-bit

2. x (Partition Type)
   - a : A-only
   - b : A/B

3. y (Build Variant)
   - v : Vanilla (no Google Apps or proprietary apps)
   - o : GApps Go (lightweight Google Apps)
   - g : GApps (standard Google Apps)
   - f : FLOSS (Free and open source apps included)

4. Z (Superuser Inclusion)
   - N : No superuser (non-rooted)
   - S : Superuser included (rooted)

Examples:
1. arm64_avN
   - Architecture: ARM64
   - Partition Type: A-only
   - Build Variant: Vanilla (no GApps)
   - Superuser: No superuser

2. arm_bfS
   - Architecture: ARM 32-bit
   - Partition Type: A/B
   - Build Variant: FLOSS (open-source apps)
   - Superuser: Included

3. a64_ogN
   - Architecture: ARM 32-bit with 64-bit binder
   - Partition Type: A-only
   - Build Variant: GApps Go
   - Superuser: No superuser

4. arm64_bgS
   - Architecture: ARM64
   - Partition Type: A/B
   - Build Variant: GApps (standard)
   - Superuser: Included

5. arm64_bgN
   - Architecture: ARM64
   - Partition Type: A/B
   - Build Variant: GApps (standard)
   - Superuser: Not Included
