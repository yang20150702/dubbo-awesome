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
# Warmup Iteration   1: 4.937 ops/ms
# Warmup Iteration   2: 11.894 ops/ms
# Warmup Iteration   3: 12.253 ops/ms
Iteration   1: 12.403 ops/ms
Iteration   2: 12.577 ops/ms
Iteration   3: 12.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.534 ±(99.9%) 2.119 ops/ms [Average]
  (min, avg, max) = (12.403, 12.534, 12.623), stdev = 0.116
  CI (99.9%): [10.415, 14.654] (assumes normal distribution)


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
# Warmup Iteration   1: 7.557 ops/ms
# Warmup Iteration   2: 12.824 ops/ms
# Warmup Iteration   3: 12.880 ops/ms
Iteration   1: 12.847 ops/ms
Iteration   2: 12.986 ops/ms
Iteration   3: 13.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.956 ±(99.9%) 1.779 ops/ms [Average]
  (min, avg, max) = (12.847, 12.956, 13.035), stdev = 0.098
  CI (99.9%): [11.177, 14.735] (assumes normal distribution)


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
# Warmup Iteration   1: 7.419 ops/ms
# Warmup Iteration   2: 12.224 ops/ms
# Warmup Iteration   3: 12.632 ops/ms
Iteration   1: 12.658 ops/ms
Iteration   2: 12.691 ops/ms
Iteration   3: 12.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.703 ±(99.9%) 0.945 ops/ms [Average]
  (min, avg, max) = (12.658, 12.703, 12.760), stdev = 0.052
  CI (99.9%): [11.758, 13.648] (assumes normal distribution)


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
# Warmup Iteration   1: 6.652 ops/ms
# Warmup Iteration   2: 10.225 ops/ms
# Warmup Iteration   3: 10.524 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.541 ops/ms
Iteration   3: 10.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.549 ±(99.9%) 0.476 ops/ms [Average]
  (min, avg, max) = (10.528, 10.549, 10.578), stdev = 0.026
  CI (99.9%): [10.073, 11.025] (assumes normal distribution)


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.005 ms/op
Iteration   1: 2.589 ±(99.9%) 0.005 ms/op
Iteration   2: 2.582 ±(99.9%) 0.005 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.573 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (2.547, 2.573, 2.589), stdev = 0.022
  CI (99.9%): [2.166, 2.979] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.476 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.487 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.476, 2.487, 2.494), stdev = 0.009
  CI (99.9%): [2.317, 2.657] (assumes normal distribution)


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.512 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (2.496, 2.512, 2.541), stdev = 0.025
  CI (99.9%): [2.056, 2.969] (assumes normal distribution)


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.005 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
Iteration   3: 3.077 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.054 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.038, 3.054, 3.077), stdev = 0.020
  CI (99.9%): [2.684, 3.425] (assumes normal distribution)


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
Iteration   1: 2.535 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  12.239 ms/op
                 createUser·p0.9999: 13.828 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  9.656 ms/op
                 createUser·p0.9999: 12.801 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  8.257 ms/op
                 createUser·p0.9999: 10.300 ms/op
                 createUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379763
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 180224 
    [ 2.500,  3.750) = 195151 
    [ 3.750,  5.000) = 3596 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.622 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.094 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  7.046 ms/op
                 existUser·p0.9999: 15.107 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.472 ms/op
                 existUser·p0.9999: 12.867 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  11.266 ms/op
                 existUser·p0.9999: 15.016 ms/op
                 existUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383068
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 187897 
    [ 2.500,  3.750) = 191231 
    [ 3.750,  5.000) = 3032 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      9.633 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     15.325 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  11.580 ms/op
                 getUser·p0.9999: 13.807 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  5.984 ms/op
                 getUser·p0.9999: 12.403 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  8.749 ms/op
                 getUser·p0.9999: 11.426 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381298
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 186400 
    [ 2.500,  3.750) = 190071 
    [ 3.750,  5.000) = 3754 
    [ 5.000,  6.250) = 626 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      6.291 ms/op
     p(99.9900) =     13.508 ms/op
     p(99.9990) =     14.519 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
Iteration   1: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.534 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.411 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  9.049 ms/op
                 listUser·p0.9999: 10.899 ms/op
                 listUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322371
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 97900 
    [ 2.500,  3.750) = 187616 
    [ 3.750,  5.000) = 30162 
    [ 5.000,  6.250) = 5338 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     11.285 ms/op
     p(99.9990) =     12.264 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.534 ± 2.119  ops/ms
ClientPb.existUser                       thrpt       3  12.956 ± 1.779  ops/ms
ClientPb.getUser                         thrpt       3  12.703 ± 0.945  ops/ms
ClientPb.listUser                        thrpt       3  10.549 ± 0.476  ops/ms
ClientPb.createUser                       avgt       3   2.573 ± 0.407   ms/op
ClientPb.existUser                        avgt       3   2.487 ± 0.170   ms/op
ClientPb.getUser                          avgt       3   2.512 ± 0.456   ms/op
ClientPb.listUser                         avgt       3   3.054 ± 0.371   ms/op
ClientPb.createUser                     sample  379763   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.711           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.622           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  383068   2.503 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.811           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.761           ms/op
ClientPb.getUser                        sample  381298   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.900           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.291           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.508           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.647           ms/op
ClientPb.listUser                       sample  322371   2.975 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.820           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.995           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.285           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.550           ms/op
