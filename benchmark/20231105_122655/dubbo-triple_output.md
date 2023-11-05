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
# Warmup Iteration   1: 2.376 ops/ms
# Warmup Iteration   2: 5.216 ops/ms
# Warmup Iteration   3: 9.195 ops/ms
Iteration   1: 9.932 ops/ms
Iteration   2: 9.621 ops/ms
Iteration   3: 9.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.820 ±(99.9%) 3.155 ops/ms [Average]
  (min, avg, max) = (9.621, 9.820, 9.932), stdev = 0.173
  CI (99.9%): [6.665, 12.976] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.566 ops/ms
# Warmup Iteration   2: 9.326 ops/ms
# Warmup Iteration   3: 9.997 ops/ms
Iteration   1: 10.351 ops/ms
Iteration   2: 10.309 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.315 ±(99.9%) 0.615 ops/ms [Average]
  (min, avg, max) = (10.284, 10.315, 10.351), stdev = 0.034
  CI (99.9%): [9.700, 10.930] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ops/ms
# Warmup Iteration   2: 9.211 ops/ms
# Warmup Iteration   3: 9.569 ops/ms
Iteration   1: 10.229 ops/ms
Iteration   2: 10.035 ops/ms
Iteration   3: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.035 ±(99.9%) 3.560 ops/ms [Average]
  (min, avg, max) = (9.839, 10.035, 10.229), stdev = 0.195
  CI (99.9%): [6.475, 13.594] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.842 ops/ms
# Warmup Iteration   2: 7.497 ops/ms
# Warmup Iteration   3: 8.262 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.408 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (8.280, 8.408, 8.511), stdev = 0.117
  CI (99.9%): [6.268, 10.548] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.209 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.003 ms/op
Iteration   1: 3.251 ±(99.9%) 0.006 ms/op
Iteration   2: 3.260 ±(99.9%) 0.003 ms/op
Iteration   3: 3.256 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.256 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (3.251, 3.256, 3.260), stdev = 0.004
  CI (99.9%): [3.177, 3.334] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.457 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.003 ms/op
Iteration   1: 3.125 ±(99.9%) 0.003 ms/op
Iteration   2: 3.108 ±(99.9%) 0.003 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.104 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (3.077, 3.104, 3.125), stdev = 0.024
  CI (99.9%): [2.662, 3.545] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.543 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.002 ms/op
Iteration   1: 3.219 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
Iteration   3: 3.150 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.150, 3.188, 3.219), stdev = 0.035
  CI (99.9%): [2.547, 3.829] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.278 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.005 ms/op
Iteration   1: 3.764 ±(99.9%) 0.004 ms/op
Iteration   2: 3.743 ±(99.9%) 0.005 ms/op
Iteration   3: 3.763 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (3.743, 3.757, 3.764), stdev = 0.012
  CI (99.9%): [3.538, 3.975] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.797 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.009 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.419 ms/op
                 createUser·p0.999:  16.040 ms/op
                 createUser·p0.9999: 18.449 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 21.328 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 3.258 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.755 ms/op
                 createUser·p0.999:  12.975 ms/op
                 createUser·p0.9999: 17.150 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299224
  mean =      3.206 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16661 
    [ 2.500,  5.000) = 278974 
    [ 5.000,  7.500) = 2910 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     14.332 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     21.530 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.274 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
Iteration   1: 3.143 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 19.327 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 22.905 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 3.180 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.385 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   6.461 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 22.276 ms/op
                 existUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302424
  mean =      3.173 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13049 
    [ 2.500,  5.000) = 283685 
    [ 5.000,  7.500) = 4720 
    [ 7.500, 10.000) = 332 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     14.158 ms/op
     p(99.9900) =     21.906 ms/op
     p(99.9990) =     23.166 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
Iteration   1: 3.262 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  16.269 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  14.631 ms/op
                 getUser·p0.9999: 22.698 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 3.238 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  11.863 ms/op
                 getUser·p0.9999: 22.057 ms/op
                 getUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295206
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6065 
    [ 2.500,  5.000) = 285033 
    [ 5.000,  7.500) = 3200 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 174 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     16.134 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.562 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.803 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.011 ms/op
Iteration   1: 3.841 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  13.835 ms/op
                 listUser·p0.9999: 19.203 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.786 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.429 ms/op
                 listUser·p0.999:  13.463 ms/op
                 listUser·p0.9999: 17.221 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.835 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.316 ms/op
                 listUser·p0.999:  12.894 ms/op
                 listUser·p0.9999: 16.400 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251083
  mean =      3.821 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 66 
    [ 2.500,  3.750) = 131295 
    [ 3.750,  5.000) = 114115 
    [ 5.000,  6.250) = 2536 
    [ 6.250,  7.500) = 1858 
    [ 7.500,  8.750) = 416 
    [ 8.750, 10.000) = 144 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 248 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     19.643 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.820 ± 3.155  ops/ms
ClientPb.existUser                       thrpt       3  10.315 ± 0.615  ops/ms
ClientPb.getUser                         thrpt       3  10.035 ± 3.560  ops/ms
ClientPb.listUser                        thrpt       3   8.408 ± 2.140  ops/ms
ClientPb.createUser                       avgt       3   3.256 ± 0.078   ms/op
ClientPb.existUser                        avgt       3   3.104 ± 0.441   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 0.641   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 0.219   ms/op
ClientPb.createUser                     sample  299224   3.206 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.876           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.332           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.480           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.758           ms/op
ClientPb.existUser                      sample  302424   3.173 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.158           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.906           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.265           ms/op
ClientPb.getUser                        sample  295206   3.251 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.134           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.086           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.691           ms/op
ClientPb.listUser                       sample  251083   3.821 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.353           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.924           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.759           ms/op
