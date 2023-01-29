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
# Warmup Iteration   1: 2.248 ops/ms
# Warmup Iteration   2: 5.770 ops/ms
# Warmup Iteration   3: 8.778 ops/ms
Iteration   1: 9.139 ops/ms
Iteration   2: 9.127 ops/ms
Iteration   3: 9.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.201 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (9.127, 9.201, 9.338), stdev = 0.119
  CI (99.9%): [7.038, 11.364] (assumes normal distribution)


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
# Warmup Iteration   1: 2.861 ops/ms
# Warmup Iteration   2: 8.868 ops/ms
# Warmup Iteration   3: 9.768 ops/ms
Iteration   1: 9.787 ops/ms
Iteration   2: 9.695 ops/ms
Iteration   3: 10.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.833 ±(99.9%) 3.028 ops/ms [Average]
  (min, avg, max) = (9.695, 9.833, 10.017), stdev = 0.166
  CI (99.9%): [6.805, 12.861] (assumes normal distribution)


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
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 8.886 ops/ms
# Warmup Iteration   3: 9.199 ops/ms
Iteration   1: 8.845 ops/ms
Iteration   2: 9.461 ops/ms
Iteration   3: 9.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.260 ±(99.9%) 6.554 ops/ms [Average]
  (min, avg, max) = (8.845, 9.260, 9.473), stdev = 0.359
  CI (99.9%): [2.706, 15.814] (assumes normal distribution)


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
# Warmup Iteration   1: 3.092 ops/ms
# Warmup Iteration   2: 7.276 ops/ms
# Warmup Iteration   3: 7.908 ops/ms
Iteration   1: 8.118 ops/ms
Iteration   2: 8.058 ops/ms
Iteration   3: 8.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.151 ±(99.9%) 2.080 ops/ms [Average]
  (min, avg, max) = (8.058, 8.151, 8.278), stdev = 0.114
  CI (99.9%): [6.071, 10.231] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.999 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.006 ms/op
Iteration   1: 3.452 ±(99.9%) 0.009 ms/op
Iteration   2: 3.391 ±(99.9%) 0.010 ms/op
Iteration   3: 3.349 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.397 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (3.349, 3.397, 3.452), stdev = 0.052
  CI (99.9%): [2.453, 4.342] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.926 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.005 ms/op
Iteration   1: 3.279 ±(99.9%) 0.006 ms/op
Iteration   2: 3.294 ±(99.9%) 0.006 ms/op
Iteration   3: 3.347 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.307 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.279, 3.307, 3.347), stdev = 0.036
  CI (99.9%): [2.658, 3.955] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.658 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.004 ms/op
Iteration   1: 3.587 ±(99.9%) 0.006 ms/op
Iteration   2: 3.402 ±(99.9%) 0.007 ms/op
Iteration   3: 3.489 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.493 ±(99.9%) 1.694 ms/op [Average]
  (min, avg, max) = (3.402, 3.493, 3.587), stdev = 0.093
  CI (99.9%): [1.798, 5.187] (assumes normal distribution)


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
# Warmup Iteration   1: 10.319 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.008 ms/op
Iteration   1: 3.926 ±(99.9%) 0.010 ms/op
Iteration   2: 3.964 ±(99.9%) 0.010 ms/op
Iteration   3: 3.964 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.951 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (3.926, 3.951, 3.964), stdev = 0.022
  CI (99.9%): [3.547, 4.356] (assumes normal distribution)


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
# Warmup Iteration   1: 9.573 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.011 ms/op
Iteration   1: 3.435 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  20.833 ms/op
                 createUser·p0.9999: 23.420 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.439 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  21.137 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.496 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 24.833 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277748
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8223 
    [ 2.500,  5.000) = 262289 
    [ 5.000,  7.500) = 6090 
    [ 7.500, 10.000) = 633 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     25.632 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 7.841 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
Iteration   1: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 29.244 ms/op
                 existUser·p1.00:   29.458 ms/op

Iteration   2: 3.242 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  12.842 ms/op
                 existUser·p0.9999: 24.974 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.237 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  10.096 ms/op
                 existUser·p0.9999: 36.839 ms/op
                 existUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292918
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7261 
    [ 2.500,  5.000) = 280215 
    [ 5.000,  7.500) = 4464 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     11.749 ms/op
     p(99.9900) =     35.436 ms/op
     p(99.9990) =     37.164 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 10.110 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.012 ms/op
Iteration   1: 3.531 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.385 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  21.082 ms/op
                 getUser·p0.9999: 27.359 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 3.719 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  23.495 ms/op
                 getUser·p0.9999: 30.966 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   3: 3.516 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  24.279 ms/op
                 getUser·p0.9999: 35.055 ms/op
                 getUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267626
  mean =      3.587 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4610 
    [ 2.500,  5.000) = 251397 
    [ 5.000,  7.500) = 10134 
    [ 7.500, 10.000) = 972 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     35.738 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 10.305 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.014 ms/op
Iteration   1: 4.105 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 25.619 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 4.158 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.912 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  16.459 ms/op
                 listUser·p0.9999: 22.620 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 3.930 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  16.524 ms/op
                 listUser·p0.9999: 20.072 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236213
  mean =      4.062 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 226787 
    [ 5.000,  7.500) = 7272 
    [ 7.500, 10.000) = 1348 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     24.482 ms/op
     p(99.9990) =     26.340 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.201 ± 2.163  ops/ms
ClientPb.existUser                       thrpt       3   9.833 ± 3.028  ops/ms
ClientPb.getUser                         thrpt       3   9.260 ± 6.554  ops/ms
ClientPb.listUser                        thrpt       3   8.151 ± 2.080  ops/ms
ClientPb.createUser                       avgt       3   3.397 ± 0.945   ms/op
ClientPb.existUser                        avgt       3   3.307 ± 0.649   ms/op
ClientPb.getUser                          avgt       3   3.493 ± 1.694   ms/op
ClientPb.listUser                         avgt       3   3.951 ± 0.405   ms/op
ClientPb.createUser                     sample  277748   3.456 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.118           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.709           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.707           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.821           ms/op
ClientPb.existUser                      sample  292918   3.276 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.749           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.436           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.290           ms/op
ClientPb.getUser                        sample  267626   3.587 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.385           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.053           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.948           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.045           ms/op
ClientPb.listUser                       sample  236213   4.062 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.696           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.482           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
