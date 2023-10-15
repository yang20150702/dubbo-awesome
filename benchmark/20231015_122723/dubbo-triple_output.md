# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.980 ops/ms
# Warmup Iteration   2: 5.433 ops/ms
# Warmup Iteration   3: 8.294 ops/ms
Iteration   1: 8.819 ops/ms
Iteration   2: 9.091 ops/ms
Iteration   3: 9.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.991 ±(99.9%) 2.737 ops/ms [Average]
  (min, avg, max) = (8.819, 8.991, 9.091), stdev = 0.150
  CI (99.9%): [6.254, 11.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.087 ops/ms
# Warmup Iteration   2: 8.539 ops/ms
# Warmup Iteration   3: 9.215 ops/ms
Iteration   1: 9.198 ops/ms
Iteration   2: 9.312 ops/ms
Iteration   3: 9.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.361 ±(99.9%) 3.496 ops/ms [Average]
  (min, avg, max) = (9.198, 9.361, 9.572), stdev = 0.192
  CI (99.9%): [5.865, 12.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.879 ops/ms
# Warmup Iteration   2: 8.114 ops/ms
# Warmup Iteration   3: 8.811 ops/ms
Iteration   1: 8.832 ops/ms
Iteration   2: 9.088 ops/ms
Iteration   3: 9.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.071 ±(99.9%) 4.206 ops/ms [Average]
  (min, avg, max) = (8.832, 9.071, 9.292), stdev = 0.231
  CI (99.9%): [4.864, 13.277] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.381 ops/ms
# Warmup Iteration   2: 7.063 ops/ms
# Warmup Iteration   3: 7.388 ops/ms
Iteration   1: 7.474 ops/ms
Iteration   2: 7.499 ops/ms
Iteration   3: 7.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.505 ±(99.9%) 0.624 ops/ms [Average]
  (min, avg, max) = (7.474, 7.505, 7.541), stdev = 0.034
  CI (99.9%): [6.880, 8.129] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.134 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.005 ms/op
Iteration   1: 3.616 ±(99.9%) 0.006 ms/op
Iteration   2: 3.618 ±(99.9%) 0.005 ms/op
Iteration   3: 3.672 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.636 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.616, 3.636, 3.672), stdev = 0.032
  CI (99.9%): [3.055, 4.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.421 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.004 ms/op
Iteration   1: 3.475 ±(99.9%) 0.004 ms/op
Iteration   2: 3.401 ±(99.9%) 0.006 ms/op
Iteration   3: 3.303 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.393 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (3.303, 3.393, 3.475), stdev = 0.087
  CI (99.9%): [1.811, 4.975] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.850 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.005 ms/op
Iteration   1: 3.514 ±(99.9%) 0.011 ms/op
Iteration   2: 3.530 ±(99.9%) 0.005 ms/op
Iteration   3: 3.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.527 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (3.514, 3.527, 3.536), stdev = 0.011
  CI (99.9%): [3.324, 3.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.250 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.006 ms/op
Iteration   1: 4.231 ±(99.9%) 0.007 ms/op
Iteration   2: 4.300 ±(99.9%) 0.004 ms/op
Iteration   3: 4.349 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.293 ±(99.9%) 1.077 ms/op [Average]
  (min, avg, max) = (4.231, 4.293, 4.349), stdev = 0.059
  CI (99.9%): [3.216, 5.370] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.337 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.011 ms/op
Iteration   1: 3.576 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.875 ms/op
                 createUser·p0.999:  15.041 ms/op
                 createUser·p0.9999: 21.596 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   2: 3.558 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  20.271 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.510 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  22.315 ms/op
                 createUser·p0.9999: 26.932 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270496
  mean =      3.548 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5331 
    [ 2.500,  5.000) = 257906 
    [ 5.000,  7.500) = 5043 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     25.885 ms/op
     p(99.9990) =     27.994 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.844 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.009 ms/op
Iteration   1: 3.387 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  19.385 ms/op
                 existUser·p0.9999: 22.086 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.461 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  21.347 ms/op
                 existUser·p0.9999: 24.338 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.379 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  23.658 ms/op
                 existUser·p0.9999: 26.952 ms/op
                 existUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281732
  mean =      3.409 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5228 
    [ 2.500,  5.000) = 268649 
    [ 5.000,  7.500) = 6099 
    [ 7.500, 10.000) = 994 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 163 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     21.472 ms/op
     p(99.9900) =     25.717 ms/op
     p(99.9990) =     32.440 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.106 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.012 ms/op
Iteration   1: 3.760 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   8.348 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 36.962 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   2: 3.529 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  9.066 ms/op
                 getUser·p0.9999: 24.344 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   3: 3.589 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  23.364 ms/op
                 getUser·p0.9999: 31.204 ms/op
                 getUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264758
  mean =      3.624 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1956 
    [ 2.500,  5.000) = 252199 
    [ 5.000,  7.500) = 8471 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     30.051 ms/op
     p(99.9990) =     37.028 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.424 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.974 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.496 ±(99.9%) 0.016 ms/op
Iteration   1: 4.361 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  21.780 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   2: 4.267 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 26.710 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 4.350 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 221715
  mean =      4.325 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 210581 
    [ 5.000,  7.500) = 7930 
    [ 7.500, 10.000) = 2142 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 269 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     25.024 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.991 ± 2.737  ops/ms
ClientPb.existUser                       thrpt       3   9.361 ± 3.496  ops/ms
ClientPb.getUser                         thrpt       3   9.071 ± 4.206  ops/ms
ClientPb.listUser                        thrpt       3   7.505 ± 0.624  ops/ms
ClientPb.createUser                       avgt       3   3.636 ± 0.581   ms/op
ClientPb.existUser                        avgt       3   3.393 ± 1.582   ms/op
ClientPb.getUser                          avgt       3   3.527 ± 0.203   ms/op
ClientPb.listUser                         avgt       3   4.293 ± 1.077   ms/op
ClientPb.createUser                     sample  270496   3.548 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.345           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.007           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.885           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.082           ms/op
ClientPb.existUser                      sample  281732   3.409 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.510           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.472           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.717           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.473           ms/op
ClientPb.getUser                        sample  264758   3.624 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.086           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.051           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  221715   4.325 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.427           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.907           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.024           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
