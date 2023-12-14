# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.731 ops/ms
# Warmup Iteration   2: 11.927 ops/ms
# Warmup Iteration   3: 12.325 ops/ms
Iteration   1: 12.518 ops/ms
Iteration   2: 12.645 ops/ms
Iteration   3: 12.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.607 ±(99.9%) 1.417 ops/ms [Average]
  (min, avg, max) = (12.518, 12.607, 12.659), stdev = 0.078
  CI (99.9%): [11.191, 14.024] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.004 ops/ms
# Warmup Iteration   2: 13.011 ops/ms
# Warmup Iteration   3: 13.151 ops/ms
Iteration   1: 13.156 ops/ms
Iteration   2: 13.230 ops/ms
Iteration   3: 13.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.197 ±(99.9%) 0.687 ops/ms [Average]
  (min, avg, max) = (13.156, 13.197, 13.230), stdev = 0.038
  CI (99.9%): [12.510, 13.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.800 ops/ms
# Warmup Iteration   2: 12.575 ops/ms
# Warmup Iteration   3: 12.788 ops/ms
Iteration   1: 13.003 ops/ms
Iteration   2: 12.953 ops/ms
Iteration   3: 12.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.971 ±(99.9%) 0.512 ops/ms [Average]
  (min, avg, max) = (12.953, 12.971, 13.003), stdev = 0.028
  CI (99.9%): [12.458, 13.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.705 ops/ms
# Warmup Iteration   2: 10.541 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.729 ops/ms
Iteration   2: 10.668 ops/ms
Iteration   3: 10.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.707 ±(99.9%) 0.619 ops/ms [Average]
  (min, avg, max) = (10.668, 10.707, 10.729), stdev = 0.034
  CI (99.9%): [10.088, 11.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.557 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.003 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.535 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.520, 2.535, 2.557), stdev = 0.020
  CI (99.9%): [2.176, 2.894] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (2.466, 2.472, 2.479), stdev = 0.006
  CI (99.9%): [2.355, 2.589] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.922 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.470, 2.486, 2.503), stdev = 0.016
  CI (99.9%): [2.187, 2.786] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.004 ms/op
Iteration   3: 2.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.976 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.970, 2.976, 2.983), stdev = 0.007
  CI (99.9%): [2.855, 3.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  11.645 ms/op
                 createUser·p0.9999: 13.382 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 13.172 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.872 ms/op
                 createUser·p0.999:  8.101 ms/op
                 createUser·p0.9999: 10.335 ms/op
                 createUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376823
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 179533 
    [ 2.500,  3.750) = 192488 
    [ 3.750,  5.000) = 3802 
    [ 5.000,  6.250) = 410 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.234 ms/op
     p(99.9900) =     13.063 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  5.920 ms/op
                 existUser·p0.9999: 14.172 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  8.557 ms/op
                 existUser·p0.9999: 13.139 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.957 ms/op
                 existUser·p0.999:  6.254 ms/op
                 existUser·p0.9999: 11.715 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392657
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 198834 
    [ 2.500,  3.750) = 190585 
    [ 3.750,  5.000) = 2323 
    [ 5.000,  6.250) = 382 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      7.821 ms/op
     p(99.9900) =     13.377 ms/op
     p(99.9990) =     14.520 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 14.584 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   2: 2.502 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.371 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.760 ms/op
                 getUser·p0.9999: 13.733 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   3: 2.468 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.388 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.700 ms/op
                 getUser·p0.9999: 14.355 ms/op
                 getUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385802
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 204235 
    [ 2.500,  3.750) = 174216 
    [ 3.750,  5.000) = 6036 
    [ 5.000,  6.250) = 752 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.417 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     14.287 ms/op
     p(99.9990) =     15.150 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.733 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.009 ms/op
Iteration   1: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.327 ms/op
                 listUser·p0.9999: 10.648 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.918 ms/op
                 listUser·p0.9999: 11.687 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   3: 3.014 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.734 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  8.894 ms/op
                 listUser·p0.9999: 10.623 ms/op
                 listUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320946
  mean =      2.988 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 97829 
    [ 2.500,  3.750) = 180929 
    [ 3.750,  5.000) = 34542 
    [ 5.000,  6.250) = 5884 
    [ 6.250,  7.500) = 763 
    [ 7.500,  8.750) = 283 
    [ 8.750, 10.000) = 287 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     11.123 ms/op
     p(99.9990) =     12.088 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


# Run complete. Total time: 00:12:56

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.607 ± 1.417  ops/ms
ClientPb.existUser                       thrpt       3  13.197 ± 0.687  ops/ms
ClientPb.getUser                         thrpt       3  12.971 ± 0.512  ops/ms
ClientPb.listUser                        thrpt       3  10.707 ± 0.619  ops/ms
ClientPb.createUser                       avgt       3   2.535 ± 0.359   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.117   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.299   ms/op
ClientPb.listUser                         avgt       3   2.976 ± 0.121   ms/op
ClientPb.createUser                     sample  376823   2.545 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.234           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.063           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  392657   2.442 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.687           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.821           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.377           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  385802   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.800           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.417           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.865           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.287           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.483           ms/op
ClientPb.listUser                       sample  320946   2.988 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.734           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.123           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.190           ms/op
