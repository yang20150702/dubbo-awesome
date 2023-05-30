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
# Warmup Iteration   1: 2.288 ops/ms
# Warmup Iteration   2: 5.263 ops/ms
# Warmup Iteration   3: 8.790 ops/ms
Iteration   1: 9.414 ops/ms
Iteration   2: 9.269 ops/ms
Iteration   3: 9.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.338 ±(99.9%) 1.332 ops/ms [Average]
  (min, avg, max) = (9.269, 9.338, 9.414), stdev = 0.073
  CI (99.9%): [8.007, 10.670] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.474 ops/ms
# Warmup Iteration   2: 8.697 ops/ms
# Warmup Iteration   3: 9.495 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.334 ops/ms
Iteration   3: 10.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.715 ±(99.9%) 6.800 ops/ms [Average]
  (min, avg, max) = (9.334, 9.715, 10.078), stdev = 0.373
  CI (99.9%): [2.915, 16.515] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.990 ops/ms
# Warmup Iteration   2: 8.307 ops/ms
# Warmup Iteration   3: 9.296 ops/ms
Iteration   1: 9.717 ops/ms
Iteration   2: 9.726 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.623 ±(99.9%) 3.116 ops/ms [Average]
  (min, avg, max) = (9.426, 9.623, 9.726), stdev = 0.171
  CI (99.9%): [6.507, 12.739] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.641 ops/ms
# Warmup Iteration   2: 7.235 ops/ms
# Warmup Iteration   3: 7.999 ops/ms
Iteration   1: 8.316 ops/ms
Iteration   2: 8.233 ops/ms
Iteration   3: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.246 ±(99.9%) 1.180 ops/ms [Average]
  (min, avg, max) = (8.189, 8.246, 8.316), stdev = 0.065
  CI (99.9%): [7.066, 9.426] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.315 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.008 ms/op
Iteration   1: 3.324 ±(99.9%) 0.011 ms/op
Iteration   2: 3.409 ±(99.9%) 0.009 ms/op
Iteration   3: 3.447 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.394 ±(99.9%) 1.151 ms/op [Average]
  (min, avg, max) = (3.324, 3.394, 3.447), stdev = 0.063
  CI (99.9%): [2.242, 4.545] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.550 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.009 ms/op
Iteration   1: 3.236 ±(99.9%) 0.009 ms/op
Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
Iteration   3: 3.239 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.236 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (3.233, 3.236, 3.239), stdev = 0.003
  CI (99.9%): [3.177, 3.295] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.232 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.007 ms/op
Iteration   1: 3.359 ±(99.9%) 0.007 ms/op
Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
Iteration   3: 3.305 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.321 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (3.298, 3.321, 3.359), stdev = 0.034
  CI (99.9%): [2.708, 3.933] (assumes normal distribution)


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
# Warmup Iteration   1: 10.536 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.009 ms/op
Iteration   1: 3.868 ±(99.9%) 0.011 ms/op
Iteration   2: 3.970 ±(99.9%) 0.007 ms/op
Iteration   3: 3.773 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.870 ±(99.9%) 1.796 ms/op [Average]
  (min, avg, max) = (3.773, 3.870, 3.970), stdev = 0.098
  CI (99.9%): [2.074, 5.666] (assumes normal distribution)


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
# Warmup Iteration   1: 8.811 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.010 ms/op
Iteration   1: 3.439 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  19.369 ms/op
                 createUser·p0.9999: 22.109 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.673 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  22.524 ms/op
                 createUser·p0.9999: 26.593 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.343 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 24.944 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284185
  mean =      3.373 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6607 
    [ 2.500,  5.000) = 272675 
    [ 5.000,  7.500) = 3729 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     18.901 ms/op
     p(99.9900) =     25.447 ms/op
     p(99.9990) =     27.170 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 8.600 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
Iteration   1: 3.140 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 22.834 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  9.202 ms/op
                 existUser·p0.9999: 23.953 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.324 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  15.437 ms/op
                 existUser·p0.9999: 23.061 ms/op
                 existUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298612
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23608 
    [ 2.500,  5.000) = 270100 
    [ 5.000,  7.500) = 4282 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 150 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =      9.839 ms/op
     p(99.9900) =     23.696 ms/op
     p(99.9990) =     24.218 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 9.102 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.011 ms/op
Iteration   1: 3.379 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  19.410 ms/op
                 getUser·p0.9999: 22.970 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.326 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  19.828 ms/op
                 getUser·p0.9999: 25.032 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.307 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  13.481 ms/op
                 getUser·p0.9999: 26.127 ms/op
                 getUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287507
  mean =      3.337 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7330 
    [ 2.500,  5.000) = 274235 
    [ 5.000,  7.500) = 5153 
    [ 7.500, 10.000) = 484 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     25.649 ms/op
     p(99.9990) =     26.669 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 9.848 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.013 ms/op
Iteration   1: 4.012 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  16.408 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 3.981 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  16.478 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 4.008 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  16.142 ms/op
                 listUser·p0.9999: 21.824 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239788
  mean =      4.000 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 230909 
    [ 5.000,  7.500) = 6284 
    [ 7.500, 10.000) = 1704 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     21.693 ms/op
     p(99.9990) =     22.296 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.338 ± 1.332  ops/ms
ClientPb.existUser                       thrpt       3   9.715 ± 6.800  ops/ms
ClientPb.getUser                         thrpt       3   9.623 ± 3.116  ops/ms
ClientPb.listUser                        thrpt       3   8.246 ± 1.180  ops/ms
ClientPb.createUser                       avgt       3   3.394 ± 1.151   ms/op
ClientPb.existUser                        avgt       3   3.236 ± 0.059   ms/op
ClientPb.getUser                          avgt       3   3.321 ± 0.612   ms/op
ClientPb.listUser                         avgt       3   3.870 ± 1.796   ms/op
ClientPb.createUser                     sample  284185   3.373 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.343           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.901           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.447           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.360           ms/op
ClientPb.existUser                      sample  298612   3.211 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.839           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.696           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.805           ms/op
ClientPb.getUser                        sample  287507   3.337 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.979           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.841           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.399           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.649           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.558           ms/op
ClientPb.listUser                       sample  239788   4.000 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.169           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.384           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.693           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.479           ms/op
