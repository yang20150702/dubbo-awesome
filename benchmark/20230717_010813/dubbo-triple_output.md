# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 5.812 ops/ms
# Warmup Iteration   3: 9.090 ops/ms
Iteration   1: 10.043 ops/ms
Iteration   2: 10.023 ops/ms
Iteration   3: 10.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.048 ±(99.9%) 0.519 ops/ms [Average]
  (min, avg, max) = (10.023, 10.048, 10.079), stdev = 0.028
  CI (99.9%): [9.530, 10.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ops/ms
# Warmup Iteration   2: 9.405 ops/ms
# Warmup Iteration   3: 10.402 ops/ms
Iteration   1: 10.238 ops/ms
Iteration   2: 10.013 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.244 ±(99.9%) 4.258 ops/ms [Average]
  (min, avg, max) = (10.013, 10.244, 10.480), stdev = 0.233
  CI (99.9%): [5.986, 14.502] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.403 ops/ms
# Warmup Iteration   2: 9.049 ops/ms
# Warmup Iteration   3: 9.752 ops/ms
Iteration   1: 10.064 ops/ms
Iteration   2: 10.367 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.238 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (10.064, 10.238, 10.367), stdev = 0.157
  CI (99.9%): [7.378, 13.098] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.281 ops/ms
# Warmup Iteration   2: 7.644 ops/ms
# Warmup Iteration   3: 8.365 ops/ms
Iteration   1: 8.381 ops/ms
Iteration   2: 8.585 ops/ms
Iteration   3: 8.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.467 ±(99.9%) 1.927 ops/ms [Average]
  (min, avg, max) = (8.381, 8.467, 8.585), stdev = 0.106
  CI (99.9%): [6.539, 10.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.292 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.005 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.005 ms/op
Iteration   3: 3.190 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.169 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.147, 3.169, 3.190), stdev = 0.022
  CI (99.9%): [2.768, 3.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.854 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.084 ±(99.9%) 0.003 ms/op
Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.076 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.043, 3.076, 3.100), stdev = 0.029
  CI (99.9%): [2.539, 3.612] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.951 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.002 ms/op
Iteration   1: 3.200 ±(99.9%) 0.004 ms/op
Iteration   2: 3.134 ±(99.9%) 0.002 ms/op
Iteration   3: 3.160 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.164 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.134, 3.164, 3.200), stdev = 0.033
  CI (99.9%): [2.559, 3.770] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.381 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.004 ms/op
Iteration   1: 3.805 ±(99.9%) 0.004 ms/op
Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
Iteration   3: 3.711 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (3.711, 3.757, 3.805), stdev = 0.047
  CI (99.9%): [2.895, 4.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.352 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  12.342 ms/op
                 createUser·p0.9999: 19.955 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 3.215 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.477 ms/op
                 createUser·p0.999:  12.823 ms/op
                 createUser·p0.9999: 23.070 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  15.292 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301695
  mean =      3.180 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11549 
    [ 2.500,  5.000) = 284717 
    [ 5.000,  7.500) = 4649 
    [ 7.500, 10.000) = 318 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     15.026 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.150 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.377 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.755 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  17.821 ms/op
                 existUser·p0.9999: 20.369 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.223 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  10.873 ms/op
                 existUser·p0.9999: 21.171 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293727
  mean =      3.265 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29495 
    [ 2.500,  5.000) = 258450 
    [ 5.000,  7.500) = 4989 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     14.373 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.575 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.348 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
Iteration   1: 3.281 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.618 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  20.527 ms/op
                 getUser·p0.9999: 25.456 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  13.648 ms/op
                 getUser·p0.9999: 19.726 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299455
  mean =      3.205 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13029 
    [ 2.500,  5.000) = 280022 
    [ 5.000,  7.500) = 5508 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     16.147 ms/op
     p(99.9900) =     23.498 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.903 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.011 ms/op
Iteration   1: 3.748 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.005 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 17.251 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   2: 3.949 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.354 ms/op
                 listUser·p0.999:  12.829 ms/op
                 listUser·p0.9999: 14.189 ms/op
                 listUser·p1.00:   14.238 ms/op

Iteration   3: 3.716 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 15.054 ms/op
                 listUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252332
  mean =      3.801 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 40 
    [ 2.500,  3.750) = 153511 
    [ 3.750,  5.000) = 91435 
    [ 5.000,  6.250) = 2877 
    [ 6.250,  7.500) = 2699 
    [ 7.500,  8.750) = 922 
    [ 8.750, 10.000) = 301 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 199 
    [12.500, 13.750) = 151 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     16.167 ms/op
     p(99.9990) =     17.840 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.048 ± 0.519  ops/ms
ClientPb.existUser                       thrpt       3  10.244 ± 4.258  ops/ms
ClientPb.getUser                         thrpt       3  10.238 ± 2.860  ops/ms
ClientPb.listUser                        thrpt       3   8.467 ± 1.927  ops/ms
ClientPb.createUser                       avgt       3   3.169 ± 0.401   ms/op
ClientPb.existUser                        avgt       3   3.076 ± 0.536   ms/op
ClientPb.getUser                          avgt       3   3.164 ± 0.605   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 0.862   ms/op
ClientPb.createUser                     sample  301695   3.180 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.953           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.026           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.774           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.822           ms/op
ClientPb.existUser                      sample  293727   3.265 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.450           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.373           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.463           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  299455   3.205 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.967           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.718           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.147           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.498           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.575           ms/op
ClientPb.listUser                       sample  252332   3.801 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.733           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.845           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.167           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.285           ms/op
