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
# Warmup Iteration   1: 4.767 ops/ms
# Warmup Iteration   2: 12.140 ops/ms
# Warmup Iteration   3: 12.416 ops/ms
Iteration   1: 12.587 ops/ms
Iteration   2: 12.669 ops/ms
Iteration   3: 12.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.685 ±(99.9%) 1.978 ops/ms [Average]
  (min, avg, max) = (12.587, 12.685, 12.801), stdev = 0.108
  CI (99.9%): [10.708, 14.663] (assumes normal distribution)


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
# Warmup Iteration   1: 8.288 ops/ms
# Warmup Iteration   2: 13.188 ops/ms
# Warmup Iteration   3: 12.989 ops/ms
Iteration   1: 13.308 ops/ms
Iteration   2: 13.297 ops/ms
Iteration   3: 13.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.294 ±(99.9%) 0.268 ops/ms [Average]
  (min, avg, max) = (13.278, 13.294, 13.308), stdev = 0.015
  CI (99.9%): [13.026, 13.563] (assumes normal distribution)


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
# Warmup Iteration   1: 7.747 ops/ms
# Warmup Iteration   2: 12.380 ops/ms
# Warmup Iteration   3: 12.826 ops/ms
Iteration   1: 13.013 ops/ms
Iteration   2: 12.939 ops/ms
Iteration   3: 12.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.952 ±(99.9%) 1.023 ops/ms [Average]
  (min, avg, max) = (12.903, 12.952, 13.013), stdev = 0.056
  CI (99.9%): [11.929, 13.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.801 ops/ms
# Warmup Iteration   2: 10.467 ops/ms
# Warmup Iteration   3: 10.627 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.579 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (10.506, 10.579, 10.633), stdev = 0.066
  CI (99.9%): [9.380, 11.777] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.494, 2.509, 2.521), stdev = 0.013
  CI (99.9%): [2.265, 2.753] (assumes normal distribution)


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.003 ms/op
Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
Iteration   3: 2.441 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.431, 2.435, 2.441), stdev = 0.005
  CI (99.9%): [2.337, 2.532] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.472 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.472, 2.478, 2.483), stdev = 0.005
  CI (99.9%): [2.378, 2.578] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.980, 2.985, 2.990), stdev = 0.005
  CI (99.9%): [2.894, 3.076] (assumes normal distribution)


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.724 ms/op
                 createUser·p0.999:  10.912 ms/op
                 createUser·p0.9999: 13.733 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.076 ms/op
                 createUser·p0.9999: 12.569 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.557 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 11.720 ms/op
                 createUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383683
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 186885 
    [ 2.500,  3.750) = 192791 
    [ 3.750,  5.000) = 3059 
    [ 5.000,  6.250) = 448 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.853 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.060 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.977 ms/op
                 existUser·p0.9999: 14.418 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  8.977 ms/op
                 existUser·p0.9999: 12.290 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388405
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 193571 
    [ 2.500,  3.750) = 191334 
    [ 3.750,  5.000) = 2619 
    [ 5.000,  6.250) = 382 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      7.689 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     14.619 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  5.710 ms/op
                 getUser·p0.9999: 14.652 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  9.462 ms/op
                 getUser·p0.9999: 13.244 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  9.170 ms/op
                 getUser·p0.9999: 11.534 ms/op
                 getUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381878
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 188215 
    [ 2.500,  3.750) = 188265 
    [ 3.750,  5.000) = 3788 
    [ 5.000,  6.250) = 1067 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.011 ms/op
     p(99.9000) =      8.391 ms/op
     p(99.9900) =     13.678 ms/op
     p(99.9990) =     16.125 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
Iteration   1: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.878 ms/op
                 listUser·p0.9999: 10.584 ms/op
                 listUser·p1.00:   10.764 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 11.052 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.642 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 11.834 ms/op
                 listUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321442
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 95748 
    [ 2.500,  3.750) = 187597 
    [ 3.750,  5.000) = 31041 
    [ 5.000,  6.250) = 5588 
    [ 6.250,  7.500) = 620 
    [ 7.500,  8.750) = 314 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     10.994 ms/op
     p(99.9990) =     12.585 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.685 ± 1.978  ops/ms
ClientPb.existUser                       thrpt       3  13.294 ± 0.268  ops/ms
ClientPb.getUser                         thrpt       3  12.952 ± 1.023  ops/ms
ClientPb.listUser                        thrpt       3  10.579 ± 1.199  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.244   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.097   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.100   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.091   ms/op
ClientPb.createUser                     sample  383683   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.557           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.853           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.189           ms/op
ClientPb.existUser                      sample  388405   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.844           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.689           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.172           ms/op
ClientPb.getUser                        sample  381878   2.511 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.685           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.011           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.391           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.678           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.237           ms/op
ClientPb.listUser                       sample  321442   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.642           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.994           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.189           ms/op
