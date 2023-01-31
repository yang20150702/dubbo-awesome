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
# Warmup Iteration   1: 2.768 ops/ms
# Warmup Iteration   2: 6.414 ops/ms
# Warmup Iteration   3: 9.194 ops/ms
Iteration   1: 9.778 ops/ms
Iteration   2: 9.776 ops/ms
Iteration   3: 10.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.906 ±(99.9%) 4.075 ops/ms [Average]
  (min, avg, max) = (9.776, 9.906, 10.164), stdev = 0.223
  CI (99.9%): [5.831, 13.982] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ops/ms
# Warmup Iteration   2: 9.675 ops/ms
# Warmup Iteration   3: 10.086 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.560 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.610 ±(99.9%) 1.004 ops/ms [Average]
  (min, avg, max) = (10.560, 10.610, 10.669), stdev = 0.055
  CI (99.9%): [9.606, 11.615] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.348 ops/ms
# Warmup Iteration   2: 9.062 ops/ms
# Warmup Iteration   3: 9.708 ops/ms
Iteration   1: 10.153 ops/ms
Iteration   2: 10.119 ops/ms
Iteration   3: 10.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.094 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (10.009, 10.094, 10.153), stdev = 0.075
  CI (99.9%): [8.723, 11.465] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.478 ops/ms
# Warmup Iteration   2: 7.765 ops/ms
# Warmup Iteration   3: 8.344 ops/ms
Iteration   1: 8.782 ops/ms
Iteration   2: 8.626 ops/ms
Iteration   3: 8.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.642 ±(99.9%) 2.413 ops/ms [Average]
  (min, avg, max) = (8.519, 8.642, 8.782), stdev = 0.132
  CI (99.9%): [6.229, 11.055] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.485 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.006 ms/op
Iteration   1: 3.150 ±(99.9%) 0.005 ms/op
Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
Iteration   3: 3.113 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.127 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (3.113, 3.127, 3.150), stdev = 0.020
  CI (99.9%): [2.757, 3.497] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.429 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.002 ms/op
Iteration   1: 3.029 ±(99.9%) 0.002 ms/op
Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
Iteration   3: 3.122 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.057 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (3.019, 3.057, 3.122), stdev = 0.057
  CI (99.9%): [2.017, 4.097] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.212 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.002 ms/op
Iteration   1: 3.261 ±(99.9%) 0.003 ms/op
Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
Iteration   3: 3.138 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.185 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.138, 3.185, 3.261), stdev = 0.066
  CI (99.9%): [1.972, 4.398] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.830 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.004 ms/op
Iteration   1: 3.711 ±(99.9%) 0.008 ms/op
Iteration   2: 3.655 ±(99.9%) 0.010 ms/op
Iteration   3: 3.736 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.701 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.655, 3.701, 3.736), stdev = 0.042
  CI (99.9%): [2.939, 4.462] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.509 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.009 ms/op
Iteration   1: 3.217 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  13.082 ms/op
                 createUser·p0.9999: 19.863 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.080 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  19.134 ms/op
                 createUser·p0.9999: 24.048 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  15.602 ms/op
                 createUser·p0.9999: 19.524 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303471
  mean =      3.160 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17506 
    [ 2.500,  5.000) = 280856 
    [ 5.000,  7.500) = 4223 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 170 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     16.656 ms/op
     p(99.9900) =     23.057 ms/op
     p(99.9990) =     24.313 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.269 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
Iteration   1: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 20.438 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  12.465 ms/op
                 existUser·p0.9999: 21.153 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  10.171 ms/op
                 existUser·p0.9999: 19.815 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310224
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23848 
    [ 2.500,  5.000) = 282592 
    [ 5.000,  7.500) = 3028 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 7.654 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
Iteration   1: 3.228 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  15.880 ms/op
                 getUser·p0.9999: 19.762 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  19.464 ms/op
                 getUser·p0.9999: 24.408 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 3.178 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 19.524 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301078
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19183 
    [ 2.500,  5.000) = 276035 
    [ 5.000,  7.500) = 4933 
    [ 7.500, 10.000) = 367 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     15.775 ms/op
     p(99.9900) =     23.491 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 8.928 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.012 ms/op
Iteration   1: 3.711 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 20.023 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.665 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.824 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.772 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  12.723 ms/op
                 listUser·p0.9999: 16.335 ms/op
                 listUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258220
  mean =      3.716 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 250954 
    [ 5.000,  7.500) = 5164 
    [ 7.500, 10.000) = 1421 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.970 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     19.175 ms/op
     p(99.9990) =     20.592 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.906 ± 4.075  ops/ms
ClientPb.existUser                       thrpt       3  10.610 ± 1.004  ops/ms
ClientPb.getUser                         thrpt       3  10.094 ± 1.371  ops/ms
ClientPb.listUser                        thrpt       3   8.642 ± 2.413  ops/ms
ClientPb.createUser                       avgt       3   3.127 ± 0.370   ms/op
ClientPb.existUser                        avgt       3   3.057 ± 1.040   ms/op
ClientPb.getUser                          avgt       3   3.185 ± 1.213   ms/op
ClientPb.listUser                         avgt       3   3.701 ± 0.762   ms/op
ClientPb.createUser                     sample  303471   3.160 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.190           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.656           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.057           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.576           ms/op
ClientPb.existUser                      sample  310224   3.091 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.775           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.365           ms/op
ClientPb.getUser                        sample  301078   3.187 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.939           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.489           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.775           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.491           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.231           ms/op
ClientPb.listUser                       sample  258220   3.716 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.970           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.175           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.644           ms/op
