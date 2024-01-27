# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.049 ops/ms
# Warmup Iteration   2: 12.051 ops/ms
# Warmup Iteration   3: 12.181 ops/ms
Iteration   1: 12.643 ops/ms
Iteration   2: 12.612 ops/ms
Iteration   3: 12.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.626 ±(99.9%) 0.286 ops/ms [Average]
  (min, avg, max) = (12.612, 12.626, 12.643), stdev = 0.016
  CI (99.9%): [12.340, 12.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.280 ops/ms
# Warmup Iteration   2: 12.924 ops/ms
# Warmup Iteration   3: 12.987 ops/ms
Iteration   1: 13.166 ops/ms
Iteration   2: 13.347 ops/ms
Iteration   3: 13.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.221 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (13.152, 13.221, 13.347), stdev = 0.109
  CI (99.9%): [11.238, 15.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.254 ops/ms
# Warmup Iteration   2: 12.819 ops/ms
# Warmup Iteration   3: 13.062 ops/ms
Iteration   1: 13.068 ops/ms
Iteration   2: 13.100 ops/ms
Iteration   3: 13.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.078 ±(99.9%) 0.344 ops/ms [Average]
  (min, avg, max) = (13.066, 13.078, 13.100), stdev = 0.019
  CI (99.9%): [12.734, 13.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.740 ops/ms
# Warmup Iteration   2: 10.539 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.673 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.680 ±(99.9%) 0.121 ops/ms [Average]
  (min, avg, max) = (10.673, 10.680, 10.686), stdev = 0.007
  CI (99.9%): [10.560, 10.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.497 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.488, 2.497, 2.513), stdev = 0.013
  CI (99.9%): [2.256, 2.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.003 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (2.440, 2.446, 2.452), stdev = 0.006
  CI (99.9%): [2.334, 2.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (2.453, 2.461, 2.472), stdev = 0.010
  CI (99.9%): [2.286, 2.636] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.644 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
Iteration   3: 2.996 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.999 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (2.996, 2.999, 3.003), stdev = 0.004
  CI (99.9%): [2.933, 3.065] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 15.115 ms/op
                 createUser·p1.00:   15.614 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.655 ms/op
                 createUser·p0.999:  8.023 ms/op
                 createUser·p0.9999: 12.362 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  8.356 ms/op
                 createUser·p0.9999: 10.668 ms/op
                 createUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386424
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 189048 
    [ 2.500,  3.750) = 193645 
    [ 3.750,  5.000) = 2902 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.323 ms/op
     p(99.9900) =     13.365 ms/op
     p(99.9990) =     15.396 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.611 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.423 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.701 ms/op
                 existUser·p0.999:  7.866 ms/op
                 existUser·p0.9999: 13.424 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 12.961 ms/op
                 existUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387447
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 186622 
    [ 2.500,  3.750) = 197611 
    [ 3.750,  5.000) = 2439 
    [ 5.000,  6.250) = 339 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.113 ms/op
     p(99.9900) =     13.013 ms/op
     p(99.9990) =     13.715 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.543 ms/op
                 getUser·p0.999:  9.529 ms/op
                 getUser·p0.9999: 13.681 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  9.793 ms/op
                 getUser·p0.9999: 22.824 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  6.433 ms/op
                 getUser·p0.9999: 11.061 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385211
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191297 
    [ 2.500,  5.000) = 192553 
    [ 5.000,  7.500) = 970 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      7.734 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     23.131 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.574 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.009 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.749 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.228 ms/op
                 listUser·p0.9999: 11.468 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.053 ms/op
                 listUser·p0.9999: 11.223 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.181 ms/op
                 listUser·p0.9999: 11.756 ms/op
                 listUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320140
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 95522 
    [ 2.500,  3.750) = 186104 
    [ 3.750,  5.000) = 31275 
    [ 5.000,  6.250) = 5588 
    [ 6.250,  7.500) = 871 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     12.521 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.626 ± 0.286  ops/ms
ClientPb.existUser                       thrpt       3  13.221 ± 1.984  ops/ms
ClientPb.getUser                         thrpt       3  13.078 ± 0.344  ops/ms
ClientPb.listUser                        thrpt       3  10.680 ± 0.121  ops/ms
ClientPb.createUser                       avgt       3   2.497 ± 0.242   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.112   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.175   ms/op
ClientPb.listUser                         avgt       3   2.999 ± 0.066   ms/op
ClientPb.createUser                     sample  386424   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.964           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.323           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.365           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.614           ms/op
ClientPb.existUser                      sample  387447   2.475 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.817           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.113           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.013           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.812           ms/op
ClientPb.getUser                        sample  385211   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.016           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.734           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.396           ms/op
ClientPb.listUser                       sample  320140   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.749           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
