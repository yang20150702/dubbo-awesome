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
# Warmup Iteration   1: 5.158 ops/ms
# Warmup Iteration   2: 11.817 ops/ms
# Warmup Iteration   3: 12.171 ops/ms
Iteration   1: 12.402 ops/ms
Iteration   2: 12.493 ops/ms
Iteration   3: 12.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.486 ±(99.9%) 1.468 ops/ms [Average]
  (min, avg, max) = (12.402, 12.486, 12.562), stdev = 0.080
  CI (99.9%): [11.017, 13.954] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 12.555 ops/ms
# Warmup Iteration   3: 12.508 ops/ms
Iteration   1: 12.548 ops/ms
Iteration   2: 12.544 ops/ms
Iteration   3: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.551 ±(99.9%) 0.181 ops/ms [Average]
  (min, avg, max) = (12.544, 12.551, 12.563), stdev = 0.010
  CI (99.9%): [12.370, 12.733] (assumes normal distribution)


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
# Warmup Iteration   1: 7.312 ops/ms
# Warmup Iteration   2: 12.195 ops/ms
# Warmup Iteration   3: 12.464 ops/ms
Iteration   1: 12.571 ops/ms
Iteration   2: 12.631 ops/ms
Iteration   3: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.602 ±(99.9%) 0.548 ops/ms [Average]
  (min, avg, max) = (12.571, 12.602, 12.631), stdev = 0.030
  CI (99.9%): [12.054, 13.150] (assumes normal distribution)


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
# Warmup Iteration   1: 6.418 ops/ms
# Warmup Iteration   2: 10.457 ops/ms
# Warmup Iteration   3: 10.490 ops/ms
Iteration   1: 10.450 ops/ms
Iteration   2: 10.536 ops/ms
Iteration   3: 10.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.491 ±(99.9%) 0.792 ops/ms [Average]
  (min, avg, max) = (10.450, 10.491, 10.536), stdev = 0.043
  CI (99.9%): [9.699, 11.283] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.600 ±(99.9%) 0.004 ms/op
Iteration   1: 2.599 ±(99.9%) 0.004 ms/op
Iteration   2: 2.560 ±(99.9%) 0.003 ms/op
Iteration   3: 2.543 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.567 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (2.543, 2.567, 2.599), stdev = 0.029
  CI (99.9%): [2.046, 3.088] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.532 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.003 ms/op
Iteration   3: 2.538 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.529 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.516, 2.529, 2.538), stdev = 0.011
  CI (99.9%): [2.322, 2.736] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.593 ±(99.9%) 0.004 ms/op
Iteration   1: 2.586 ±(99.9%) 0.004 ms/op
Iteration   2: 2.591 ±(99.9%) 0.003 ms/op
Iteration   3: 2.597 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.591 ±(99.9%) 0.093 ms/op [Average]
  (min, avg, max) = (2.586, 2.591, 2.597), stdev = 0.005
  CI (99.9%): [2.499, 2.684] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.856 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
Iteration   3: 3.026 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (3.026, 3.036, 3.054), stdev = 0.016
  CI (99.9%): [2.752, 3.320] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.727 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.593 ±(99.9%) 0.006 ms/op
Iteration   1: 2.601 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  11.993 ms/op
                 createUser·p0.9999: 14.746 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 2.593 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  6.201 ms/op
                 createUser·p0.9999: 12.796 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 2.616 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  9.176 ms/op
                 createUser·p0.9999: 21.456 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 368323
  mean =      2.603 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 173932 
    [ 2.500,  5.000) = 193441 
    [ 5.000,  7.500) = 527 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     15.398 ms/op
     p(99.9990) =     23.891 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.317 ms/op
                 existUser·p0.9999: 13.478 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  9.100 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  5.787 ms/op
                 existUser·p0.9999: 13.128 ms/op
                 existUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382745
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 184516 
    [ 2.500,  3.750) = 194554 
    [ 3.750,  5.000) = 2918 
    [ 5.000,  6.250) = 351 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 135 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      5.841 ms/op
     p(99.9900) =     13.459 ms/op
     p(99.9990) =     13.899 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  12.351 ms/op
                 getUser·p0.9999: 15.335 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.907 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 13.250 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.589 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  5.575 ms/op
                 getUser·p0.9999: 12.391 ms/op
                 getUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375087
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 181807 
    [ 2.500,  3.750) = 188292 
    [ 3.750,  5.000) = 3906 
    [ 5.000,  6.250) = 675 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      6.433 ms/op
     p(99.9900) =     14.073 ms/op
     p(99.9990) =     15.700 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.967 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.074 ms/op
                 listUser·p0.9999: 10.757 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.767 ms/op
                 listUser·p0.9999: 11.004 ms/op
                 listUser·p1.00:   11.207 ms/op

Iteration   3: 3.085 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.788 ms/op
                 listUser·p0.999:  10.213 ms/op
                 listUser·p0.9999: 14.936 ms/op
                 listUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311748
  mean =      3.077 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 80440 
    [ 2.500,  3.750) = 188005 
    [ 3.750,  5.000) = 35021 
    [ 5.000,  6.250) = 6613 
    [ 6.250,  7.500) = 938 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 235 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     13.557 ms/op
     p(99.9990) =     15.625 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.486 ± 1.468  ops/ms
ClientPb.existUser                       thrpt       3  12.551 ± 0.181  ops/ms
ClientPb.getUser                         thrpt       3  12.602 ± 0.548  ops/ms
ClientPb.listUser                        thrpt       3  10.491 ± 0.792  ops/ms
ClientPb.createUser                       avgt       3   2.567 ± 0.521   ms/op
ClientPb.existUser                        avgt       3   2.529 ± 0.207   ms/op
ClientPb.getUser                          avgt       3   2.591 ± 0.093   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.284   ms/op
ClientPb.createUser                     sample  368323   2.603 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.744           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.666           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.569           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.398           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  382745   2.506 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.753           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.841           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.459           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  375087   2.557 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.729           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.073           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.056           ms/op
ClientPb.listUser                       sample  311748   3.077 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.934           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.557           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.794           ms/op
