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
# Warmup Iteration   1: 5.332 ops/ms
# Warmup Iteration   2: 12.247 ops/ms
# Warmup Iteration   3: 12.421 ops/ms
Iteration   1: 12.781 ops/ms
Iteration   2: 12.609 ops/ms
Iteration   3: 12.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.712 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (12.609, 12.712, 12.781), stdev = 0.091
  CI (99.9%): [11.060, 14.364] (assumes normal distribution)


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
# Warmup Iteration   1: 8.258 ops/ms
# Warmup Iteration   2: 13.113 ops/ms
# Warmup Iteration   3: 13.049 ops/ms
Iteration   1: 13.047 ops/ms
Iteration   2: 13.105 ops/ms
Iteration   3: 13.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.056 ±(99.9%) 0.827 ops/ms [Average]
  (min, avg, max) = (13.016, 13.056, 13.105), stdev = 0.045
  CI (99.9%): [12.229, 13.883] (assumes normal distribution)


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
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 12.471 ops/ms
# Warmup Iteration   3: 12.803 ops/ms
Iteration   1: 12.972 ops/ms
Iteration   2: 12.823 ops/ms
Iteration   3: 12.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.841 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (12.729, 12.841, 12.972), stdev = 0.123
  CI (99.9%): [10.602, 15.080] (assumes normal distribution)


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
# Warmup Iteration   1: 6.714 ops/ms
# Warmup Iteration   2: 10.692 ops/ms
# Warmup Iteration   3: 10.788 ops/ms
Iteration   1: 10.827 ops/ms
Iteration   2: 10.832 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.783 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (10.691, 10.783, 10.832), stdev = 0.080
  CI (99.9%): [9.318, 12.249] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.003 ms/op
Iteration   2: 2.551 ±(99.9%) 0.003 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.536 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.519, 2.536, 2.551), stdev = 0.016
  CI (99.9%): [2.247, 2.826] (assumes normal distribution)


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.004 ms/op
Iteration   1: 2.435 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
Iteration   3: 2.434 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (2.434, 2.462, 2.517), stdev = 0.047
  CI (99.9%): [1.596, 3.328] (assumes normal distribution)


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.453 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.440, 2.453, 2.476), stdev = 0.020
  CI (99.9%): [2.092, 2.815] (assumes normal distribution)


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
Iteration   3: 2.985 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.969, 2.977, 2.985), stdev = 0.008
  CI (99.9%): [2.832, 3.122] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.876 ms/op
                 createUser·p0.999:  11.381 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 13.556 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  8.565 ms/op
                 createUser·p0.9999: 10.695 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379437
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183088 
    [ 2.500,  5.000) = 195401 
    [ 5.000,  7.500) = 545 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     14.546 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  7.054 ms/op
                 existUser·p0.9999: 15.923 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  6.356 ms/op
                 existUser·p0.9999: 13.663 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.823 ms/op
                 existUser·p0.999:  6.641 ms/op
                 existUser·p0.9999: 11.090 ms/op
                 existUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393191
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 199096 
    [ 2.500,  3.750) = 190213 
    [ 3.750,  5.000) = 3022 
    [ 5.000,  6.250) = 390 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      6.713 ms/op
     p(99.9900) =     14.091 ms/op
     p(99.9990) =     16.401 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  11.407 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 14.847 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  9.064 ms/op
                 getUser·p0.9999: 12.164 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383484
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 190837 
    [ 2.500,  3.750) = 189089 
    [ 3.750,  5.000) = 2849 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      9.069 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     15.515 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
Iteration   1: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 12.603 ms/op
                 listUser·p1.00:   13.844 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.883 ms/op
                 listUser·p0.9999: 11.321 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.732 ms/op
                 listUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321643
  mean =      2.982 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 96395 
    [ 2.500,  3.750) = 188425 
    [ 3.750,  5.000) = 29943 
    [ 5.000,  6.250) = 5548 
    [ 6.250,  7.500) = 560 
    [ 7.500,  8.750) = 173 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     13.694 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.712 ± 1.652  ops/ms
ClientPb.existUser                       thrpt       3  13.056 ± 0.827  ops/ms
ClientPb.getUser                         thrpt       3  12.841 ± 2.239  ops/ms
ClientPb.listUser                        thrpt       3  10.783 ± 1.465  ops/ms
ClientPb.createUser                       avgt       3   2.536 ± 0.290   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.866   ms/op
ClientPb.getUser                          avgt       3   2.453 ± 0.361   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.145   ms/op
ClientPb.createUser                     sample  379437   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.599           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.087           ms/op
ClientPb.existUser                      sample  393191   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.713           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.810           ms/op
ClientPb.getUser                        sample  383484   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.945           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.069           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.828           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.171           ms/op
ClientPb.listUser                       sample  321643   2.982 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.844           ms/op
