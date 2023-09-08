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
# Warmup Iteration   1: 2.048 ops/ms
# Warmup Iteration   2: 5.302 ops/ms
# Warmup Iteration   3: 8.219 ops/ms
Iteration   1: 8.814 ops/ms
Iteration   2: 9.052 ops/ms
Iteration   3: 9.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.135 ±(99.9%) 6.735 ops/ms [Average]
  (min, avg, max) = (8.814, 9.135, 9.539), stdev = 0.369
  CI (99.9%): [2.400, 15.870] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.169 ops/ms
# Warmup Iteration   2: 8.821 ops/ms
# Warmup Iteration   3: 9.531 ops/ms
Iteration   1: 9.613 ops/ms
Iteration   2: 9.626 ops/ms
Iteration   3: 9.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.684 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (9.613, 9.684, 9.812), stdev = 0.111
  CI (99.9%): [7.651, 11.717] (assumes normal distribution)


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
# Warmup Iteration   1: 3.100 ops/ms
# Warmup Iteration   2: 8.524 ops/ms
# Warmup Iteration   3: 9.357 ops/ms
Iteration   1: 9.224 ops/ms
Iteration   2: 9.400 ops/ms
Iteration   3: 9.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.346 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (9.224, 9.346, 9.413), stdev = 0.106
  CI (99.9%): [7.414, 11.277] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.606 ops/ms
# Warmup Iteration   2: 6.777 ops/ms
# Warmup Iteration   3: 7.734 ops/ms
Iteration   1: 7.745 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 8.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.902 ±(99.9%) 3.048 ops/ms [Average]
  (min, avg, max) = (7.745, 7.902, 8.077), stdev = 0.167
  CI (99.9%): [4.853, 10.950] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.800 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.004 ms/op
Iteration   1: 3.418 ±(99.9%) 0.007 ms/op
Iteration   2: 3.402 ±(99.9%) 0.008 ms/op
Iteration   3: 3.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.457 ±(99.9%) 1.507 ms/op [Average]
  (min, avg, max) = (3.402, 3.457, 3.552), stdev = 0.083
  CI (99.9%): [1.950, 4.965] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.010 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.004 ms/op
Iteration   1: 3.325 ±(99.9%) 0.004 ms/op
Iteration   2: 3.409 ±(99.9%) 0.007 ms/op
Iteration   3: 3.391 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.375 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.325, 3.375, 3.409), stdev = 0.044
  CI (99.9%): [2.566, 4.184] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.682 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.004 ms/op
Iteration   1: 3.635 ±(99.9%) 0.006 ms/op
Iteration   2: 3.591 ±(99.9%) 0.003 ms/op
Iteration   3: 3.625 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.617 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.591, 3.617, 3.635), stdev = 0.023
  CI (99.9%): [3.190, 4.044] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 11.091 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.011 ms/op
Iteration   1: 3.966 ±(99.9%) 0.012 ms/op
Iteration   2: 3.967 ±(99.9%) 0.011 ms/op
Iteration   3: 4.030 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.988 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.966, 3.988, 4.030), stdev = 0.037
  CI (99.9%): [3.321, 4.655] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 11.320 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.015 ms/op
Iteration   1: 3.482 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  20.257 ms/op
                 createUser·p0.9999: 23.298 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   2: 3.571 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  15.773 ms/op
                 createUser·p0.9999: 25.956 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   3: 3.425 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  24.642 ms/op
                 createUser·p0.9999: 43.188 ms/op
                 createUser·p1.00:   43.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274847
  mean =      3.491 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 266989 
    [ 5.000, 10.000) = 7347 
    [10.000, 15.000) = 161 
    [15.000, 20.000) = 46 
    [20.000, 25.000) = 202 
    [25.000, 30.000) = 68 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     40.928 ms/op
     p(99.9990) =     43.434 ms/op
     p(99.9999) =     43.647 ms/op
    p(100.0000) =     43.647 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.084 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.009 ms/op
Iteration   1: 3.469 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  20.395 ms/op
                 existUser·p0.9999: 23.356 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.623 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.415 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.527 ms/op
                 existUser·p0.999:  22.355 ms/op
                 existUser·p0.9999: 30.757 ms/op
                 existUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274203
  mean =      3.500 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12474 
    [ 2.500,  5.000) = 252302 
    [ 5.000,  7.500) = 7678 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     13.776 ms/op
     p(99.9900) =     28.612 ms/op
     p(99.9990) =     30.975 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 9.827 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.820 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.011 ms/op
Iteration   1: 3.577 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  20.611 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.424 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  21.416 ms/op
                 getUser·p0.9999: 24.488 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  19.502 ms/op
                 getUser·p0.9999: 27.558 ms/op
                 getUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274235
  mean =      3.499 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6414 
    [ 2.500,  5.000) = 257918 
    [ 5.000,  7.500) = 7982 
    [ 7.500, 10.000) = 1349 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     20.031 ms/op
     p(99.9900) =     25.447 ms/op
     p(99.9990) =     27.894 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 11.283 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.015 ms/op
Iteration   1: 4.058 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  21.509 ms/op
                 listUser·p0.9999: 24.652 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 4.121 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 4.096 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  14.597 ms/op
                 listUser·p0.9999: 17.668 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234588
  mean =      4.091 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 224923 
    [ 5.000,  7.500) = 6393 
    [ 7.500, 10.000) = 2234 
    [10.000, 12.500) = 452 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     26.487 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.135 ± 6.735  ops/ms
ClientPb.existUser                       thrpt       3   9.684 ± 2.033  ops/ms
ClientPb.getUser                         thrpt       3   9.346 ± 1.932  ops/ms
ClientPb.listUser                        thrpt       3   7.902 ± 3.048  ops/ms
ClientPb.createUser                       avgt       3   3.457 ± 1.507   ms/op
ClientPb.existUser                        avgt       3   3.375 ± 0.809   ms/op
ClientPb.getUser                          avgt       3   3.617 ± 0.427   ms/op
ClientPb.listUser                         avgt       3   3.988 ± 0.667   ms/op
ClientPb.createUser                     sample  274847   3.491 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.974           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.644           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.928           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.647           ms/op
ClientPb.existUser                      sample  274203   3.500 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.106           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.612           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.776           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.612           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.261           ms/op
ClientPb.getUser                        sample  274235   3.499 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.723           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.031           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.447           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.049           ms/op
ClientPb.listUser                       sample  234588   4.091 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.313           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.822           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.608           ms/op
