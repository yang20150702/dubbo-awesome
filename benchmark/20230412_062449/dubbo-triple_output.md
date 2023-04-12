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
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 5.167 ops/ms
# Warmup Iteration   3: 8.537 ops/ms
Iteration   1: 9.035 ops/ms
Iteration   2: 9.303 ops/ms
Iteration   3: 9.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.240 ±(99.9%) 3.313 ops/ms [Average]
  (min, avg, max) = (9.035, 9.240, 9.381), stdev = 0.182
  CI (99.9%): [5.927, 12.552] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.736 ops/ms
# Warmup Iteration   2: 8.192 ops/ms
# Warmup Iteration   3: 9.539 ops/ms
Iteration   1: 9.348 ops/ms
Iteration   2: 9.860 ops/ms
Iteration   3: 9.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.634 ±(99.9%) 4.762 ops/ms [Average]
  (min, avg, max) = (9.348, 9.634, 9.860), stdev = 0.261
  CI (99.9%): [4.872, 14.396] (assumes normal distribution)


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
# Warmup Iteration   1: 2.775 ops/ms
# Warmup Iteration   2: 8.215 ops/ms
# Warmup Iteration   3: 9.067 ops/ms
Iteration   1: 9.229 ops/ms
Iteration   2: 9.429 ops/ms
Iteration   3: 9.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.328 ±(99.9%) 1.826 ops/ms [Average]
  (min, avg, max) = (9.229, 9.328, 9.429), stdev = 0.100
  CI (99.9%): [7.501, 11.154] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.553 ops/ms
# Warmup Iteration   2: 6.953 ops/ms
# Warmup Iteration   3: 7.578 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 8.064 ops/ms
Iteration   3: 8.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.980 ±(99.9%) 3.487 ops/ms [Average]
  (min, avg, max) = (7.761, 7.980, 8.114), stdev = 0.191
  CI (99.9%): [4.493, 11.466] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.117 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.009 ms/op
Iteration   1: 3.552 ±(99.9%) 0.013 ms/op
Iteration   2: 3.470 ±(99.9%) 0.009 ms/op
Iteration   3: 3.532 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.518 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (3.470, 3.518, 3.552), stdev = 0.042
  CI (99.9%): [2.743, 4.292] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.352 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.004 ms/op
Iteration   1: 3.270 ±(99.9%) 0.005 ms/op
Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
Iteration   3: 3.246 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.278 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.246, 3.278, 3.317), stdev = 0.036
  CI (99.9%): [2.617, 3.938] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.377 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.567 ±(99.9%) 0.006 ms/op
Iteration   1: 3.481 ±(99.9%) 0.010 ms/op
Iteration   2: 3.404 ±(99.9%) 0.006 ms/op
Iteration   3: 3.487 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.457 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.404, 3.457, 3.487), stdev = 0.046
  CI (99.9%): [2.611, 4.304] (assumes normal distribution)


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
# Warmup Iteration   1: 11.026 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.008 ms/op
Iteration   1: 4.197 ±(99.9%) 0.009 ms/op
Iteration   2: 3.998 ±(99.9%) 0.010 ms/op
Iteration   3: 3.966 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.054 ±(99.9%) 2.285 ms/op [Average]
  (min, avg, max) = (3.966, 4.054, 4.197), stdev = 0.125
  CI (99.9%): [1.769, 6.339] (assumes normal distribution)


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
# Warmup Iteration   1: 10.362 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.013 ms/op
Iteration   1: 3.501 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  19.423 ms/op
                 createUser·p0.9999: 29.511 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   2: 3.523 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.207 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  21.561 ms/op
                 createUser·p0.9999: 28.205 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.835 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.097 ms/op
                 createUser·p0.999:  24.960 ms/op
                 createUser·p0.9999: 29.426 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277420
  mean =      3.465 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8663 
    [ 2.500,  5.000) = 261763 
    [ 5.000,  7.500) = 5966 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     20.715 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     30.015 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 8.565 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.009 ms/op
Iteration   1: 3.466 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  20.357 ms/op
                 existUser·p0.9999: 23.155 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.289 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  16.325 ms/op
                 existUser·p0.9999: 24.773 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   3: 3.619 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   5.752 ms/op
                 existUser·p0.999:  22.140 ms/op
                 existUser·p0.9999: 41.943 ms/op
                 existUser·p1.00:   42.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277848
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270992 
    [ 5.000, 10.000) = 6492 
    [10.000, 15.000) = 57 
    [15.000, 20.000) = 52 
    [20.000, 25.000) = 186 
    [25.000, 30.000) = 37 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     16.354 ms/op
     p(99.9900) =     39.257 ms/op
     p(99.9990) =     42.154 ms/op
     p(99.9999) =     42.467 ms/op
    p(100.0000) =     42.467 ms/op


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
# Warmup Iteration   1: 10.488 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.009 ms/op
Iteration   1: 3.559 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  19.403 ms/op
                 getUser·p0.9999: 27.427 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   2: 3.477 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  21.430 ms/op
                 getUser·p0.9999: 24.038 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 3.551 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  17.994 ms/op
                 getUser·p0.9999: 25.002 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271879
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2616 
    [ 2.500,  5.000) = 257457 
    [ 5.000,  7.500) = 10124 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     26.470 ms/op
     p(99.9990) =     27.946 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 10.866 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.013 ms/op
Iteration   1: 4.118 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  20.298 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 3.963 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.166 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.433 ms/op
                 listUser·p0.999:  16.706 ms/op
                 listUser·p0.9999: 24.000 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237539
  mean =      4.039 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 228974 
    [ 5.000,  7.500) = 6167 
    [ 7.500, 10.000) = 1492 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     16.792 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     24.269 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.240 ± 3.313  ops/ms
ClientPb.existUser                       thrpt       3   9.634 ± 4.762  ops/ms
ClientPb.getUser                         thrpt       3   9.328 ± 1.826  ops/ms
ClientPb.listUser                        thrpt       3   7.980 ± 3.487  ops/ms
ClientPb.createUser                       avgt       3   3.518 ± 0.775   ms/op
ClientPb.existUser                        avgt       3   3.278 ± 0.661   ms/op
ClientPb.getUser                          avgt       3   3.457 ± 0.847   ms/op
ClientPb.listUser                         avgt       3   4.054 ± 2.285   ms/op
ClientPb.createUser                     sample  277420   3.465 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.597           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.715           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.295           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  277848   3.453 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.346           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.354           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.257           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.467           ms/op
ClientPb.getUser                        sample  271879   3.528 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.005           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.470           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.180           ms/op
ClientPb.listUser                       sample  237539   4.039 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.792           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.757           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
