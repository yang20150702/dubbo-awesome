# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.708 ops/ms
# Warmup Iteration   2: 6.682 ops/ms
# Warmup Iteration   3: 9.161 ops/ms
Iteration   1: 10.086 ops/ms
Iteration   2: 9.775 ops/ms
Iteration   3: 9.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.858 ±(99.9%) 3.642 ops/ms [Average]
  (min, avg, max) = (9.713, 9.858, 10.086), stdev = 0.200
  CI (99.9%): [6.216, 13.500] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.567 ops/ms
# Warmup Iteration   2: 9.442 ops/ms
# Warmup Iteration   3: 9.922 ops/ms
Iteration   1: 10.527 ops/ms
Iteration   2: 10.101 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.401 ±(99.9%) 4.764 ops/ms [Average]
  (min, avg, max) = (10.101, 10.401, 10.575), stdev = 0.261
  CI (99.9%): [5.637, 15.165] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.520 ops/ms
# Warmup Iteration   2: 9.308 ops/ms
# Warmup Iteration   3: 9.519 ops/ms
Iteration   1: 10.001 ops/ms
Iteration   2: 9.608 ops/ms
Iteration   3: 10.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.977 ±(99.9%) 6.540 ops/ms [Average]
  (min, avg, max) = (9.608, 9.977, 10.324), stdev = 0.358
  CI (99.9%): [3.437, 16.518] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.368 ops/ms
# Warmup Iteration   2: 7.933 ops/ms
# Warmup Iteration   3: 8.231 ops/ms
Iteration   1: 8.473 ops/ms
Iteration   2: 8.589 ops/ms
Iteration   3: 8.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.624 ±(99.9%) 3.121 ops/ms [Average]
  (min, avg, max) = (8.473, 8.624, 8.810), stdev = 0.171
  CI (99.9%): [5.503, 11.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.811 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.004 ms/op
Iteration   1: 3.183 ±(99.9%) 0.007 ms/op
Iteration   2: 3.094 ±(99.9%) 0.011 ms/op
Iteration   3: 3.249 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.175 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (3.094, 3.175, 3.249), stdev = 0.078
  CI (99.9%): [1.759, 4.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.264 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
Iteration   2: 3.007 ±(99.9%) 0.004 ms/op
Iteration   3: 3.035 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.029 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.007, 3.029, 3.043), stdev = 0.019
  CI (99.9%): [2.683, 3.374] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.046 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.006 ms/op
Iteration   2: 3.113 ±(99.9%) 0.005 ms/op
Iteration   3: 3.247 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.137 ±(99.9%) 1.822 ms/op [Average]
  (min, avg, max) = (3.052, 3.137, 3.247), stdev = 0.100
  CI (99.9%): [1.315, 4.960] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.130 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.006 ms/op
Iteration   1: 3.753 ±(99.9%) 0.004 ms/op
Iteration   2: 3.655 ±(99.9%) 0.010 ms/op
Iteration   3: 3.696 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.701 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.655, 3.701, 3.753), stdev = 0.049
  CI (99.9%): [2.804, 4.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.261 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.009 ms/op
Iteration   1: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  12.812 ms/op
                 createUser·p0.9999: 21.391 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  14.139 ms/op
                 createUser·p0.9999: 23.455 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305274
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33460 
    [ 2.500,  5.000) = 266995 
    [ 5.000,  7.500) = 4102 
    [ 7.500, 10.000) = 288 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     21.756 ms/op
     p(99.9990) =     23.591 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.484 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.043 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  12.763 ms/op
                 existUser·p0.9999: 19.053 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.763 ms/op
                 existUser·p0.9999: 23.027 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   3: 3.530 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  16.123 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298576
  mean =      3.214 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23195 
    [ 2.500,  5.000) = 261392 
    [ 5.000,  7.500) = 12764 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     14.280 ms/op
     p(99.9900) =     22.001 ms/op
     p(99.9990) =     23.791 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.824 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.009 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.971 ms/op
                 getUser·p0.999:  15.499 ms/op
                 getUser·p0.9999: 18.875 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 20.639 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  11.763 ms/op
                 getUser·p0.9999: 20.904 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301327
  mean =      3.184 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8546 
    [ 2.500,  5.000) = 285518 
    [ 5.000,  7.500) = 6342 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 204 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.732 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     21.757 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.846 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.011 ms/op
Iteration   1: 3.818 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  16.040 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  14.437 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 3.641 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   3.764 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.059 ms/op
                 listUser·p0.9999: 14.434 ms/op
                 listUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257483
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 249732 
    [ 5.000,  7.500) = 5472 
    [ 7.500, 10.000) = 1530 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     19.219 ms/op
     p(99.9990) =     21.275 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.858 ± 3.642  ops/ms
ClientPb.existUser                       thrpt       3  10.401 ± 4.764  ops/ms
ClientPb.getUser                         thrpt       3   9.977 ± 6.540  ops/ms
ClientPb.listUser                        thrpt       3   8.624 ± 3.121  ops/ms
ClientPb.createUser                       avgt       3   3.175 ± 1.416   ms/op
ClientPb.existUser                        avgt       3   3.029 ± 0.345   ms/op
ClientPb.getUser                          avgt       3   3.137 ± 1.822   ms/op
ClientPb.listUser                         avgt       3   3.701 ± 0.898   ms/op
ClientPb.createUser                     sample  305274   3.142 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.869           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.123           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.756           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.953           ms/op
ClientPb.existUser                      sample  298576   3.214 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.892           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.280           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.001           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.084           ms/op
ClientPb.getUser                        sample  301327   3.184 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.098           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.732           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.597           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.120           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.348           ms/op
ClientPb.listUser                       sample  257483   3.727 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.393           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.219           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.496           ms/op
