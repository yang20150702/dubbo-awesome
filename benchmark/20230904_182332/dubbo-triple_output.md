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
# Warmup Iteration   1: 2.187 ops/ms
# Warmup Iteration   2: 5.584 ops/ms
# Warmup Iteration   3: 8.323 ops/ms
Iteration   1: 9.308 ops/ms
Iteration   2: 9.569 ops/ms
Iteration   3: 9.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.399 ±(99.9%) 2.683 ops/ms [Average]
  (min, avg, max) = (9.308, 9.399, 9.569), stdev = 0.147
  CI (99.9%): [6.716, 12.082] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.022 ops/ms
# Warmup Iteration   2: 8.428 ops/ms
# Warmup Iteration   3: 9.188 ops/ms
Iteration   1: 9.408 ops/ms
Iteration   2: 9.436 ops/ms
Iteration   3: 9.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.337 ±(99.9%) 2.694 ops/ms [Average]
  (min, avg, max) = (9.168, 9.337, 9.436), stdev = 0.148
  CI (99.9%): [6.643, 12.031] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.351 ops/ms
# Warmup Iteration   3: 8.987 ops/ms
Iteration   1: 9.068 ops/ms
Iteration   2: 9.268 ops/ms
Iteration   3: 9.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.169 ±(99.9%) 1.824 ops/ms [Average]
  (min, avg, max) = (9.068, 9.169, 9.268), stdev = 0.100
  CI (99.9%): [7.345, 10.994] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.463 ops/ms
# Warmup Iteration   2: 6.501 ops/ms
# Warmup Iteration   3: 7.583 ops/ms
Iteration   1: 7.652 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 7.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.786 ±(99.9%) 2.219 ops/ms [Average]
  (min, avg, max) = (7.652, 7.786, 7.890), stdev = 0.122
  CI (99.9%): [5.567, 10.005] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.629 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.004 ms/op
Iteration   1: 3.685 ±(99.9%) 0.005 ms/op
Iteration   2: 3.553 ±(99.9%) 0.008 ms/op
Iteration   3: 3.436 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.558 ±(99.9%) 2.279 ms/op [Average]
  (min, avg, max) = (3.436, 3.558, 3.685), stdev = 0.125
  CI (99.9%): [1.279, 5.837] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.339 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.003 ms/op
Iteration   1: 3.416 ±(99.9%) 0.004 ms/op
Iteration   2: 3.442 ±(99.9%) 0.005 ms/op
Iteration   3: 3.432 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.430 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (3.416, 3.430, 3.442), stdev = 0.014
  CI (99.9%): [3.183, 3.677] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.732 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.005 ms/op
Iteration   1: 3.508 ±(99.9%) 0.008 ms/op
Iteration   2: 3.549 ±(99.9%) 0.007 ms/op
Iteration   3: 3.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.527 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.508, 3.527, 3.549), stdev = 0.021
  CI (99.9%): [3.151, 3.904] (assumes normal distribution)


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
# Warmup Iteration   1: 11.281 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.422 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.007 ms/op
Iteration   1: 4.148 ±(99.9%) 0.008 ms/op
Iteration   2: 3.985 ±(99.9%) 0.008 ms/op
Iteration   3: 3.937 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.023 ±(99.9%) 2.020 ms/op [Average]
  (min, avg, max) = (3.937, 4.023, 4.148), stdev = 0.111
  CI (99.9%): [2.003, 6.044] (assumes normal distribution)


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
# Warmup Iteration   1: 9.479 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.009 ms/op
Iteration   1: 3.421 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  22.529 ms/op
                 createUser·p0.9999: 24.991 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.495 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  22.577 ms/op
                 createUser·p0.9999: 25.276 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   3: 3.539 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  12.894 ms/op
                 createUser·p0.9999: 26.410 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275383
  mean =      3.485 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4935 
    [ 2.500,  5.000) = 264104 
    [ 5.000,  7.500) = 4916 
    [ 7.500, 10.000) = 983 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 174 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     25.509 ms/op
     p(99.9990) =     27.402 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 9.128 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.008 ms/op
Iteration   1: 3.365 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  19.954 ms/op
                 existUser·p0.9999: 32.899 ms/op
                 existUser·p1.00:   33.522 ms/op

Iteration   2: 3.443 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  20.418 ms/op
                 existUser·p0.9999: 24.075 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.066 ms/op
                 existUser·p0.999:  20.370 ms/op
                 existUser·p0.9999: 26.444 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281396
  mean =      3.409 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7458 
    [ 2.500,  5.000) = 265016 
    [ 5.000,  7.500) = 7383 
    [ 7.500, 10.000) = 1056 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     20.238 ms/op
     p(99.9900) =     31.135 ms/op
     p(99.9990) =     33.462 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 9.584 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.012 ms/op
Iteration   1: 3.543 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  20.831 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.422 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  21.962 ms/op
                 getUser·p0.9999: 25.264 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  20.734 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273999
  mean =      3.500 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5891 
    [ 2.500,  5.000) = 258603 
    [ 5.000,  7.500) = 7641 
    [ 7.500, 10.000) = 1294 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 157 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.266 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 10.671 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.015 ms/op
Iteration   1: 4.146 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  22.011 ms/op
                 listUser·p0.9999: 30.254 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   2: 4.144 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  16.037 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.130 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  14.592 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231871
  mean =      4.140 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 219253 
    [ 5.000,  7.500) = 8639 
    [ 7.500, 10.000) = 2591 
    [10.000, 12.500) = 830 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     16.257 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     32.443 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.399 ± 2.683  ops/ms
ClientPb.existUser                       thrpt       3   9.337 ± 2.694  ops/ms
ClientPb.getUser                         thrpt       3   9.169 ± 1.824  ops/ms
ClientPb.listUser                        thrpt       3   7.786 ± 2.219  ops/ms
ClientPb.createUser                       avgt       3   3.558 ± 2.279   ms/op
ClientPb.existUser                        avgt       3   3.430 ± 0.247   ms/op
ClientPb.getUser                          avgt       3   3.527 ± 0.377   ms/op
ClientPb.listUser                         avgt       3   4.023 ± 2.020   ms/op
ClientPb.createUser                     sample  275383   3.485 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.479           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.250           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.513           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.509           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  281396   3.409 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.284           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.135           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.522           ms/op
ClientPb.getUser                        sample  273999   3.500 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.520           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.668           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.808           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.625           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.460           ms/op
ClientPb.listUser                       sample  231871   4.140 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.672           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.735           ms/op
