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
# Warmup Iteration   1: 4.831 ops/ms
# Warmup Iteration   2: 12.093 ops/ms
# Warmup Iteration   3: 12.255 ops/ms
Iteration   1: 12.362 ops/ms
Iteration   2: 12.378 ops/ms
Iteration   3: 12.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.384 ±(99.9%) 0.471 ops/ms [Average]
  (min, avg, max) = (12.362, 12.384, 12.413), stdev = 0.026
  CI (99.9%): [11.913, 12.856] (assumes normal distribution)


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
# Warmup Iteration   1: 8.412 ops/ms
# Warmup Iteration   2: 13.162 ops/ms
# Warmup Iteration   3: 12.955 ops/ms
Iteration   1: 12.896 ops/ms
Iteration   2: 12.898 ops/ms
Iteration   3: 12.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.862 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (12.791, 12.862, 12.898), stdev = 0.061
  CI (99.9%): [11.745, 13.978] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.184 ops/ms
# Warmup Iteration   2: 12.267 ops/ms
# Warmup Iteration   3: 12.477 ops/ms
Iteration   1: 12.548 ops/ms
Iteration   2: 12.491 ops/ms
Iteration   3: 12.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.541 ±(99.9%) 0.852 ops/ms [Average]
  (min, avg, max) = (12.491, 12.541, 12.584), stdev = 0.047
  CI (99.9%): [11.689, 13.393] (assumes normal distribution)


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
# Warmup Iteration   1: 6.503 ops/ms
# Warmup Iteration   2: 10.453 ops/ms
# Warmup Iteration   3: 10.483 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.559 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.568 ±(99.9%) 1.806 ops/ms [Average]
  (min, avg, max) = (10.473, 10.568, 10.671), stdev = 0.099
  CI (99.9%): [8.761, 12.374] (assumes normal distribution)


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
# Warmup Iteration   1: 4.277 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.521 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.508, 2.521, 2.529), stdev = 0.012
  CI (99.9%): [2.307, 2.736] (assumes normal distribution)


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.003 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
Iteration   2: 2.452 ±(99.9%) 0.003 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.461 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.452, 2.461, 2.475), stdev = 0.012
  CI (99.9%): [2.239, 2.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.005 ms/op
Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
Iteration   3: 2.551 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.542 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.527, 2.542, 2.551), stdev = 0.013
  CI (99.9%): [2.298, 2.787] (assumes normal distribution)


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.004 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
Iteration   3: 3.050 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.012, 3.036, 3.050), stdev = 0.021
  CI (99.9%): [2.661, 3.410] (assumes normal distribution)


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.514 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  10.800 ms/op
                 createUser·p0.9999: 14.077 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  7.563 ms/op
                 createUser·p0.9999: 13.830 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  8.326 ms/op
                 createUser·p0.9999: 10.371 ms/op
                 createUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385633
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 187611 
    [ 2.500,  3.750) = 194203 
    [ 3.750,  5.000) = 2974 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.370 ms/op
     p(99.9900) =     13.553 ms/op
     p(99.9990) =     14.619 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.607 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.181 ms/op
                 existUser·p0.9999: 13.369 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.266 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.780 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 11.881 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388893
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 191789 
    [ 2.500,  3.750) = 194208 
    [ 3.750,  5.000) = 2197 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      6.616 ms/op
     p(99.9900) =     12.785 ms/op
     p(99.9990) =     13.865 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  11.033 ms/op
                 getUser·p0.9999: 13.170 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  7.551 ms/op
                 getUser·p0.9999: 11.963 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  7.671 ms/op
                 getUser·p0.9999: 11.264 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379134
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 185045 
    [ 2.500,  3.750) = 188607 
    [ 3.750,  5.000) = 4103 
    [ 5.000,  6.250) = 823 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      7.596 ms/op
     p(99.9900) =     12.537 ms/op
     p(99.9990) =     13.481 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.552 ms/op
                 listUser·p0.999:  9.250 ms/op
                 listUser·p0.9999: 11.393 ms/op
                 listUser·p1.00:   13.648 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 12.850 ms/op
                 listUser·p1.00:   13.533 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.753 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.321 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 12.099 ms/op
                 listUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320133
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 92148 
    [ 2.500,  3.750) = 190573 
    [ 3.750,  5.000) = 30929 
    [ 5.000,  6.250) = 5133 
    [ 6.250,  7.500) = 541 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.486 ms/op
     p(99.9000) =      9.353 ms/op
     p(99.9900) =     12.157 ms/op
     p(99.9990) =     13.300 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.384 ± 0.471  ops/ms
ClientPb.existUser                       thrpt       3  12.862 ± 1.117  ops/ms
ClientPb.getUser                         thrpt       3  12.541 ± 0.852  ops/ms
ClientPb.listUser                        thrpt       3  10.568 ± 1.806  ops/ms
ClientPb.createUser                       avgt       3   2.521 ± 0.215   ms/op
ClientPb.existUser                        avgt       3   2.461 ± 0.222   ms/op
ClientPb.getUser                          avgt       3   2.542 ± 0.244   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.375   ms/op
ClientPb.createUser                     sample  385633   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.514           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.370           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.553           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  388893   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.782           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.616           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.785           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.107           ms/op
ClientPb.getUser                        sample  379134   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.978           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.596           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.537           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.550           ms/op
ClientPb.listUser                       sample  320133   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.486           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.353           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.157           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.648           ms/op
