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
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.643 ops/ms
# Warmup Iteration   3: 8.790 ops/ms
Iteration   1: 9.237 ops/ms
Iteration   2: 9.311 ops/ms
Iteration   3: 9.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.319 ±(99.9%) 1.592 ops/ms [Average]
  (min, avg, max) = (9.237, 9.319, 9.411), stdev = 0.087
  CI (99.9%): [7.727, 10.912] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.080 ops/ms
# Warmup Iteration   2: 9.154 ops/ms
# Warmup Iteration   3: 9.100 ops/ms
Iteration   1: 9.798 ops/ms
Iteration   2: 9.592 ops/ms
Iteration   3: 9.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.647 ±(99.9%) 2.403 ops/ms [Average]
  (min, avg, max) = (9.552, 9.647, 9.798), stdev = 0.132
  CI (99.9%): [7.244, 12.051] (assumes normal distribution)


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
# Warmup Iteration   1: 3.089 ops/ms
# Warmup Iteration   2: 8.248 ops/ms
# Warmup Iteration   3: 9.154 ops/ms
Iteration   1: 9.210 ops/ms
Iteration   2: 9.292 ops/ms
Iteration   3: 9.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.223 ±(99.9%) 1.158 ops/ms [Average]
  (min, avg, max) = (9.167, 9.223, 9.292), stdev = 0.063
  CI (99.9%): [8.065, 10.381] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.705 ops/ms
# Warmup Iteration   2: 7.272 ops/ms
# Warmup Iteration   3: 7.708 ops/ms
Iteration   1: 7.859 ops/ms
Iteration   2: 7.826 ops/ms
Iteration   3: 7.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.805 ±(99.9%) 1.223 ops/ms [Average]
  (min, avg, max) = (7.730, 7.805, 7.859), stdev = 0.067
  CI (99.9%): [6.583, 9.028] (assumes normal distribution)


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
# Warmup Iteration   1: 10.047 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.004 ms/op
Iteration   1: 3.540 ±(99.9%) 0.003 ms/op
Iteration   2: 3.472 ±(99.9%) 0.004 ms/op
Iteration   3: 3.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.508 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (3.472, 3.508, 3.540), stdev = 0.034
  CI (99.9%): [2.886, 4.129] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.802 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.006 ms/op
Iteration   1: 3.261 ±(99.9%) 0.003 ms/op
Iteration   2: 3.343 ±(99.9%) 0.004 ms/op
Iteration   3: 3.300 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.301 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (3.261, 3.301, 3.343), stdev = 0.041
  CI (99.9%): [2.554, 4.049] (assumes normal distribution)


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
# Warmup Iteration   1: 9.291 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.003 ms/op
Iteration   1: 3.409 ±(99.9%) 0.003 ms/op
Iteration   2: 3.402 ±(99.9%) 0.003 ms/op
Iteration   3: 3.419 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.410 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (3.402, 3.410, 3.419), stdev = 0.008
  CI (99.9%): [3.259, 3.561] (assumes normal distribution)


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
# Warmup Iteration   1: 11.210 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.004 ms/op
Iteration   1: 4.037 ±(99.9%) 0.007 ms/op
Iteration   2: 4.135 ±(99.9%) 0.006 ms/op
Iteration   3: 4.052 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.075 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (4.037, 4.075, 4.135), stdev = 0.053
  CI (99.9%): [3.113, 5.036] (assumes normal distribution)


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
# Warmup Iteration   1: 10.556 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.014 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.680 ms/op
                 createUser·p0.999:  19.104 ms/op
                 createUser·p0.9999: 23.249 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.373 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  22.249 ms/op
                 createUser·p0.9999: 27.264 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.418 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  13.260 ms/op
                 createUser·p0.9999: 22.291 ms/op
                 createUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282695
  mean =      3.396 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7801 
    [ 2.500,  5.000) = 270272 
    [ 5.000,  7.500) = 3600 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.736 ms/op
     p(99.9900) =     26.402 ms/op
     p(99.9990) =     27.895 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 9.973 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
Iteration   1: 3.328 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  19.602 ms/op
                 existUser·p0.9999: 24.150 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  20.783 ms/op
                 existUser·p0.9999: 24.922 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.334 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.564 ms/op
                 existUser·p0.999:  11.668 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286471
  mean =      3.351 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11776 
    [ 2.500,  5.000) = 270233 
    [ 5.000,  7.500) = 3499 
    [ 7.500, 10.000) = 391 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 165 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     14.918 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     25.282 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 9.220 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
Iteration   1: 3.532 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  12.403 ms/op
                 getUser·p0.9999: 22.442 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.412 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.912 ms/op
                 getUser·p0.999:  21.865 ms/op
                 getUser·p0.9999: 26.006 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  18.433 ms/op
                 getUser·p0.9999: 27.360 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274642
  mean =      3.494 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2324 
    [ 2.500,  5.000) = 263916 
    [ 5.000,  7.500) = 7083 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     16.734 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     28.074 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 9.644 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.012 ms/op
Iteration   1: 4.126 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.931 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 4.193 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  15.718 ms/op
                 listUser·p0.9999: 18.067 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.064 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 16.161 ms/op
                 listUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232470
  mean =      4.127 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 224722 
    [ 5.000,  7.500) = 6074 
    [ 7.500, 10.000) = 819 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 218 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.056 ms/op
     p(99.9000) =     15.623 ms/op
     p(99.9900) =     23.028 ms/op
     p(99.9990) =     24.381 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.319 ± 1.592  ops/ms
ClientPb.existUser                       thrpt       3   9.647 ± 2.403  ops/ms
ClientPb.getUser                         thrpt       3   9.223 ± 1.158  ops/ms
ClientPb.listUser                        thrpt       3   7.805 ± 1.223  ops/ms
ClientPb.createUser                       avgt       3   3.508 ± 0.621   ms/op
ClientPb.existUser                        avgt       3   3.301 ± 0.747   ms/op
ClientPb.getUser                          avgt       3   3.410 ± 0.151   ms/op
ClientPb.listUser                         avgt       3   4.075 ± 0.961   ms/op
ClientPb.createUser                     sample  282695   3.396 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.956           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.736           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.410           ms/op
ClientPb.existUser                      sample  286471   3.351 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.918           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.642           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  274642   3.494 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.300           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.734           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.837           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.312           ms/op
ClientPb.listUser                       sample  232470   4.127 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.147           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.056           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.623           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.028           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.510           ms/op
