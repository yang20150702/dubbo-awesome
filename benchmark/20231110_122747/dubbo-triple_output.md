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
# Warmup Iteration   2: 11.600 ops/ms
# Warmup Iteration   3: 11.978 ops/ms
Iteration   1: 12.180 ops/ms
Iteration   2: 12.428 ops/ms
Iteration   3: 12.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.330 ±(99.9%) 2.408 ops/ms [Average]
  (min, avg, max) = (12.180, 12.330, 12.428), stdev = 0.132
  CI (99.9%): [9.922, 14.737] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.794 ops/ms
# Warmup Iteration   2: 12.837 ops/ms
# Warmup Iteration   3: 12.988 ops/ms
Iteration   1: 12.869 ops/ms
Iteration   2: 12.910 ops/ms
Iteration   3: 12.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.901 ±(99.9%) 0.527 ops/ms [Average]
  (min, avg, max) = (12.869, 12.901, 12.925), stdev = 0.029
  CI (99.9%): [12.374, 13.428] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.366 ops/ms
# Warmup Iteration   2: 12.556 ops/ms
# Warmup Iteration   3: 12.702 ops/ms
Iteration   1: 12.960 ops/ms
Iteration   2: 12.991 ops/ms
Iteration   3: 12.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.952 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (12.905, 12.952, 12.991), stdev = 0.043
  CI (99.9%): [12.159, 13.745] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.944 ops/ms
# Warmup Iteration   2: 10.682 ops/ms
# Warmup Iteration   3: 10.648 ops/ms
Iteration   1: 10.774 ops/ms
Iteration   2: 10.560 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.651 ±(99.9%) 2.008 ops/ms [Average]
  (min, avg, max) = (10.560, 10.651, 10.774), stdev = 0.110
  CI (99.9%): [8.643, 12.659] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.008 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
Iteration   2: 2.574 ±(99.9%) 0.005 ms/op
Iteration   3: 2.559 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (2.512, 2.548, 2.574), stdev = 0.033
  CI (99.9%): [1.955, 3.142] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.745 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
Iteration   2: 2.444 ±(99.9%) 0.003 ms/op
Iteration   3: 2.454 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (2.441, 2.447, 2.454), stdev = 0.007
  CI (99.9%): [2.323, 2.570] (assumes normal distribution)


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.003 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (2.471, 2.492, 2.507), stdev = 0.018
  CI (99.9%): [2.155, 2.829] (assumes normal distribution)


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
# Warmup Iteration   1: 4.771 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.005 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
Iteration   2: 3.003 ±(99.9%) 0.007 ms/op
Iteration   3: 3.018 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.012 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (3.003, 3.012, 3.018), stdev = 0.008
  CI (99.9%): [2.860, 3.165] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.039 ms/op
                 createUser·p0.999:  12.534 ms/op
                 createUser·p0.9999: 16.761 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  9.081 ms/op
                 createUser·p0.9999: 11.635 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 10.863 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379702
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182594 
    [ 2.500,  5.000) = 195846 
    [ 5.000,  7.500) = 737 
    [ 7.500, 10.000) = 243 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     15.632 ms/op
     p(99.9990) =     18.389 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  12.194 ms/op
                 existUser·p0.9999: 14.779 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  9.017 ms/op
                 existUser·p0.9999: 14.348 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  5.731 ms/op
                 existUser·p0.9999: 13.621 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379756
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 184401 
    [ 2.500,  3.750) = 190257 
    [ 3.750,  5.000) = 3912 
    [ 5.000,  6.250) = 752 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 130 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     14.434 ms/op
     p(99.9990) =     15.912 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  11.754 ms/op
                 getUser·p0.9999: 13.766 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  7.564 ms/op
                 getUser·p0.9999: 13.896 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  8.509 ms/op
                 getUser·p0.9999: 12.426 ms/op
                 getUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382129
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 188350 
    [ 2.500,  3.750) = 189172 
    [ 3.750,  5.000) = 3405 
    [ 5.000,  6.250) = 702 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     13.644 ms/op
     p(99.9990) =     14.699 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.641 ms/op
                 listUser·p0.999:  9.205 ms/op
                 listUser·p0.9999: 11.559 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.188 ms/op
                 listUser·p0.9999: 12.296 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.355 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316277
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 90983 
    [ 2.500,  3.750) = 183552 
    [ 3.750,  5.000) = 33353 
    [ 5.000,  6.250) = 6977 
    [ 6.250,  7.500) = 623 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 238 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.515 ms/op
     p(99.9900) =     12.059 ms/op
     p(99.9990) =     12.799 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.330 ± 2.408  ops/ms
ClientPb.existUser                       thrpt       3  12.901 ± 0.527  ops/ms
ClientPb.getUser                         thrpt       3  12.952 ± 0.793  ops/ms
ClientPb.listUser                        thrpt       3  10.651 ± 2.008  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.594   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.124   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.337   ms/op
ClientPb.listUser                         avgt       3   3.012 ± 0.152   ms/op
ClientPb.createUser                     sample  379702   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.322           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.632           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.872           ms/op
ClientPb.existUser                      sample  379756   2.526 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.808           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.521           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.434           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.007           ms/op
ClientPb.getUser                        sample  382129   2.510 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.844           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.503           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.644           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  316277   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.850           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.515           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
