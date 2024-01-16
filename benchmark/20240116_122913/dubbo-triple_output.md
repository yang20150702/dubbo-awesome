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
# Warmup Iteration   1: 5.030 ops/ms
# Warmup Iteration   2: 12.075 ops/ms
# Warmup Iteration   3: 12.721 ops/ms
Iteration   1: 12.934 ops/ms
Iteration   2: 13.029 ops/ms
Iteration   3: 12.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.926 ±(99.9%) 1.939 ops/ms [Average]
  (min, avg, max) = (12.817, 12.926, 13.029), stdev = 0.106
  CI (99.9%): [10.987, 14.865] (assumes normal distribution)


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
# Warmup Iteration   1: 8.440 ops/ms
# Warmup Iteration   2: 13.276 ops/ms
# Warmup Iteration   3: 13.099 ops/ms
Iteration   1: 13.052 ops/ms
Iteration   2: 13.064 ops/ms
Iteration   3: 12.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.027 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (12.964, 13.027, 13.064), stdev = 0.055
  CI (99.9%): [12.032, 14.022] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.720 ops/ms
# Warmup Iteration   2: 12.706 ops/ms
# Warmup Iteration   3: 12.658 ops/ms
Iteration   1: 12.834 ops/ms
Iteration   2: 13.046 ops/ms
Iteration   3: 12.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.946 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (12.834, 12.946, 13.046), stdev = 0.106
  CI (99.9%): [11.010, 14.882] (assumes normal distribution)


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
# Warmup Iteration   1: 7.075 ops/ms
# Warmup Iteration   2: 10.805 ops/ms
# Warmup Iteration   3: 10.762 ops/ms
Iteration   1: 10.904 ops/ms
Iteration   2: 10.858 ops/ms
Iteration   3: 10.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.863 ±(99.9%) 0.699 ops/ms [Average]
  (min, avg, max) = (10.828, 10.863, 10.904), stdev = 0.038
  CI (99.9%): [10.164, 11.562] (assumes normal distribution)


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.003 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (2.477, 2.498, 2.525), stdev = 0.025
  CI (99.9%): [2.050, 2.945] (assumes normal distribution)


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.003 ms/op
Iteration   2: 2.424 ±(99.9%) 0.004 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.437 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.424, 2.437, 2.446), stdev = 0.012
  CI (99.9%): [2.219, 2.656] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.003 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.486, 2.504, 2.514), stdev = 0.015
  CI (99.9%): [2.228, 2.779] (assumes normal distribution)


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
Iteration   3: 2.980 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.959, 2.968, 2.980), stdev = 0.010
  CI (99.9%): [2.779, 3.158] (assumes normal distribution)


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  11.473 ms/op
                 createUser·p0.9999: 14.134 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  10.191 ms/op
                 createUser·p0.9999: 12.293 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  9.210 ms/op
                 createUser·p0.9999: 11.229 ms/op
                 createUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381301
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 185330 
    [ 2.500,  3.750) = 192434 
    [ 3.750,  5.000) = 2566 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 134 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     13.203 ms/op
     p(99.9990) =     14.385 ms/op
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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.412 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.377 ±(99.9%) 0.005 ms/op
Iteration   1: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.388 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 13.756 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  8.422 ms/op
                 existUser·p0.9999: 13.708 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  8.880 ms/op
                 existUser·p0.9999: 12.799 ms/op
                 existUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398272
  mean =      2.408 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 209826 
    [ 2.500,  3.750) = 184795 
    [ 3.750,  5.000) = 2832 
    [ 5.000,  6.250) = 216 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.425 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     13.470 ms/op
     p(99.9990) =     14.058 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  11.388 ms/op
                 getUser·p0.9999: 13.982 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 14.942 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   3: 2.537 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.365 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 32.925 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380428
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189631 
    [ 2.500,  5.000) = 189995 
    [ 5.000,  7.500) = 402 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      9.447 ms/op
     p(99.9900) =     15.008 ms/op
     p(99.9990) =     33.829 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
Iteration   1: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 11.375 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   2: 2.935 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.913 ms/op
                 listUser·p0.9999: 11.634 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.031 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324973
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 181 
    [ 1.250,  2.500) = 102175 
    [ 2.500,  3.750) = 187190 
    [ 3.750,  5.000) = 29309 
    [ 5.000,  6.250) = 4849 
    [ 6.250,  7.500) = 538 
    [ 7.500,  8.750) = 315 
    [ 8.750, 10.000) = 263 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     11.452 ms/op
     p(99.9990) =     12.243 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.926 ± 1.939  ops/ms
ClientPb.existUser                       thrpt       3  13.027 ± 0.995  ops/ms
ClientPb.getUser                         thrpt       3  12.946 ± 1.936  ops/ms
ClientPb.listUser                        thrpt       3  10.863 ± 0.699  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.448   ms/op
ClientPb.existUser                        avgt       3   2.437 ± 0.219   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.275   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.189   ms/op
ClientPb.createUser                     sample  381301   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.842           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.203           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  398272   2.408 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.611           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.425           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.848           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.470           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  380428   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.365           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.447           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.008           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  324973   2.951 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.792           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.884           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.452           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.632           ms/op
