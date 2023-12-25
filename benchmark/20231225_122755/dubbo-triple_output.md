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
# Warmup Iteration   1: 5.092 ops/ms
# Warmup Iteration   2: 12.236 ops/ms
# Warmup Iteration   3: 12.160 ops/ms
Iteration   1: 12.438 ops/ms
Iteration   2: 12.713 ops/ms
Iteration   3: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.595 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (12.438, 12.595, 12.713), stdev = 0.142
  CI (99.9%): [10.013, 15.178] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.890 ops/ms
# Warmup Iteration   2: 12.867 ops/ms
# Warmup Iteration   3: 12.829 ops/ms
Iteration   1: 12.932 ops/ms
Iteration   2: 12.854 ops/ms
Iteration   3: 12.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.845 ±(99.9%) 1.670 ops/ms [Average]
  (min, avg, max) = (12.749, 12.845, 12.932), stdev = 0.092
  CI (99.9%): [11.175, 14.515] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.712 ops/ms
# Warmup Iteration   2: 12.488 ops/ms
# Warmup Iteration   3: 12.732 ops/ms
Iteration   1: 12.943 ops/ms
Iteration   2: 13.065 ops/ms
Iteration   3: 13.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.022 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (12.943, 13.022, 13.065), stdev = 0.068
  CI (99.9%): [11.773, 14.272] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.004 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 10.598 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.650 ±(99.9%) 0.181 ops/ms [Average]
  (min, avg, max) = (10.643, 10.650, 10.662), stdev = 0.010
  CI (99.9%): [10.469, 10.832] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.993 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.003 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
Iteration   3: 2.501 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (2.471, 2.504, 2.541), stdev = 0.035
  CI (99.9%): [1.857, 3.152] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.004 ms/op
Iteration   1: 2.436 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.416, 2.430, 2.438), stdev = 0.012
  CI (99.9%): [2.204, 2.656] (assumes normal distribution)


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.482 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.468, 2.482, 2.501), stdev = 0.017
  CI (99.9%): [2.164, 2.799] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.598 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.004 ms/op
Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
Iteration   3: 2.984 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.984, 2.996, 3.002), stdev = 0.010
  CI (99.9%): [2.808, 3.184] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.017 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.698 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  11.163 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.469 ms/op
                 createUser·p0.999:  8.501 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.808 ms/op
                 createUser·p0.999:  8.282 ms/op
                 createUser·p0.9999: 11.370 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380065
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182950 
    [ 2.500,  5.000) = 196261 
    [ 5.000,  7.500) = 458 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.314 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     22.996 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.893 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  7.674 ms/op
                 existUser·p0.9999: 12.683 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  8.455 ms/op
                 existUser·p0.9999: 13.833 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385391
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 186680 
    [ 2.500,  3.750) = 195734 
    [ 3.750,  5.000) = 2293 
    [ 5.000,  6.250) = 200 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      8.353 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.423 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.689 ms/op
                 getUser·p0.999:  11.219 ms/op
                 getUser·p0.9999: 15.970 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 14.287 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.311 ms/op
                 getUser·p0.9999: 10.273 ms/op
                 getUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382661
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 190234 
    [ 2.500,  3.750) = 187897 
    [ 3.750,  5.000) = 3503 
    [ 5.000,  6.250) = 567 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     16.746 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.776 ms/op
                 listUser·p0.9999: 11.445 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.215 ms/op
                 listUser·p0.9999: 11.300 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.944 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320736
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 95864 
    [ 2.500,  3.750) = 188282 
    [ 3.750,  5.000) = 29741 
    [ 5.000,  6.250) = 5446 
    [ 6.250,  7.500) = 625 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.649 ms/op
     p(99.9990) =     12.130 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.595 ± 2.582  ops/ms
ClientPb.existUser                       thrpt       3  12.845 ± 1.670  ops/ms
ClientPb.getUser                         thrpt       3  13.022 ± 1.249  ops/ms
ClientPb.listUser                        thrpt       3  10.650 ± 0.181  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.647   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.226   ms/op
ClientPb.getUser                          avgt       3   2.482 ± 0.318   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.188   ms/op
ClientPb.createUser                     sample  380065   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.314           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.811           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.233           ms/op
ClientPb.existUser                      sample  385391   2.488 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.741           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.353           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.565           ms/op
ClientPb.getUser                        sample  382661   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.921           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.315           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.320           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.334           ms/op
ClientPb.listUser                       sample  320736   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.926           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.649           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.714           ms/op
