# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.327 ops/ms
# Warmup Iteration   2: 6.159 ops/ms
# Warmup Iteration   3: 8.617 ops/ms
Iteration   1: 9.118 ops/ms
Iteration   2: 9.450 ops/ms
Iteration   3: 9.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.225 ±(99.9%) 3.567 ops/ms [Average]
  (min, avg, max) = (9.106, 9.225, 9.450), stdev = 0.196
  CI (99.9%): [5.658, 12.791] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ops/ms
# Warmup Iteration   2: 9.083 ops/ms
# Warmup Iteration   3: 9.944 ops/ms
Iteration   1: 9.821 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 10.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.966 ±(99.9%) 2.490 ops/ms [Average]
  (min, avg, max) = (9.821, 9.966, 10.092), stdev = 0.136
  CI (99.9%): [7.476, 12.455] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.033 ops/ms
# Warmup Iteration   2: 8.485 ops/ms
# Warmup Iteration   3: 9.233 ops/ms
Iteration   1: 9.169 ops/ms
Iteration   2: 9.760 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.506 ±(99.9%) 5.549 ops/ms [Average]
  (min, avg, max) = (9.169, 9.506, 9.760), stdev = 0.304
  CI (99.9%): [3.958, 15.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.900 ops/ms
# Warmup Iteration   2: 7.507 ops/ms
# Warmup Iteration   3: 7.750 ops/ms
Iteration   1: 8.004 ops/ms
Iteration   2: 8.065 ops/ms
Iteration   3: 8.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.093 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (8.004, 8.093, 8.210), stdev = 0.106
  CI (99.9%): [6.160, 10.026] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.585 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.007 ms/op
Iteration   1: 3.353 ±(99.9%) 0.009 ms/op
Iteration   2: 3.404 ±(99.9%) 0.007 ms/op
Iteration   3: 3.312 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.356 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (3.312, 3.356, 3.404), stdev = 0.046
  CI (99.9%): [2.519, 4.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.719 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.007 ms/op
Iteration   1: 3.287 ±(99.9%) 0.014 ms/op
Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
Iteration   3: 3.244 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.261 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.244, 3.261, 3.287), stdev = 0.023
  CI (99.9%): [2.834, 3.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.836 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.004 ms/op
Iteration   1: 3.557 ±(99.9%) 0.006 ms/op
Iteration   2: 3.319 ±(99.9%) 0.006 ms/op
Iteration   3: 3.412 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.429 ±(99.9%) 2.180 ms/op [Average]
  (min, avg, max) = (3.319, 3.429, 3.557), stdev = 0.119
  CI (99.9%): [1.249, 5.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.334 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.006 ms/op
Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
Iteration   2: 3.839 ±(99.9%) 0.014 ms/op
Iteration   3: 3.903 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.910 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (3.839, 3.910, 3.988), stdev = 0.075
  CI (99.9%): [2.543, 5.277] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.488 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.011 ms/op
Iteration   1: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  19.962 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.290 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  12.114 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   3: 3.383 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 25.577 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285462
  mean =      3.359 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3583 
    [ 2.500,  5.000) = 276051 
    [ 5.000,  7.500) = 4891 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     19.535 ms/op
     p(99.9900) =     24.981 ms/op
     p(99.9990) =     26.037 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.586 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
Iteration   1: 3.257 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  10.287 ms/op
                 existUser·p0.9999: 23.966 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.296 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 30.569 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   3: 3.253 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  15.247 ms/op
                 existUser·p0.9999: 33.707 ms/op
                 existUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293472
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16139 
    [ 2.500,  5.000) = 272305 
    [ 5.000,  7.500) = 4247 
    [ 7.500, 10.000) = 329 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     32.395 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.642 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.009 ms/op
Iteration   1: 3.475 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  22.051 ms/op
                 getUser·p0.9999: 24.864 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   2: 3.493 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.976 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  24.123 ms/op
                 getUser·p0.9999: 29.776 ms/op
                 getUser·p1.00:   35.127 ms/op

Iteration   3: 3.584 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  19.261 ms/op
                 getUser·p0.9999: 27.364 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272878
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13262 
    [ 2.500,  5.000) = 248939 
    [ 5.000,  7.500) = 9192 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     29.187 ms/op
     p(99.9990) =     30.745 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.530 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.561 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.014 ms/op
Iteration   1: 3.921 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  20.655 ms/op
                 listUser·p0.9999: 24.004 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 4.115 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 19.930 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 3.883 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 18.925 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241787
  mean =      3.971 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 233242 
    [ 5.000,  7.500) = 6369 
    [ 7.500, 10.000) = 1187 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     16.289 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.225 ± 3.567  ops/ms
ClientPb.existUser                       thrpt       3   9.966 ± 2.490  ops/ms
ClientPb.getUser                         thrpt       3   9.506 ± 5.549  ops/ms
ClientPb.listUser                        thrpt       3   8.093 ± 1.933  ops/ms
ClientPb.createUser                       avgt       3   3.356 ± 0.837   ms/op
ClientPb.existUser                        avgt       3   3.261 ± 0.426   ms/op
ClientPb.getUser                          avgt       3   3.429 ± 2.180   ms/op
ClientPb.listUser                         avgt       3   3.910 ± 1.367   ms/op
ClientPb.createUser                     sample  285462   3.359 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.535           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.981           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  293472   3.269 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.206           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.395           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  272878   3.517 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.999           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.628           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.187           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  241787   3.971 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.378           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.289           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.807           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
