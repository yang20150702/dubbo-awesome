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
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 4.986 ops/ms
# Warmup Iteration   3: 8.641 ops/ms
Iteration   1: 8.826 ops/ms
Iteration   2: 9.164 ops/ms
Iteration   3: 9.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.098 ±(99.9%) 4.492 ops/ms [Average]
  (min, avg, max) = (8.826, 9.098, 9.305), stdev = 0.246
  CI (99.9%): [4.606, 13.590] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ops/ms
# Warmup Iteration   2: 8.613 ops/ms
# Warmup Iteration   3: 9.394 ops/ms
Iteration   1: 9.725 ops/ms
Iteration   2: 9.667 ops/ms
Iteration   3: 9.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.669 ±(99.9%) 1.011 ops/ms [Average]
  (min, avg, max) = (9.615, 9.669, 9.725), stdev = 0.055
  CI (99.9%): [8.659, 10.680] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.442 ops/ms
# Warmup Iteration   2: 8.598 ops/ms
# Warmup Iteration   3: 8.772 ops/ms
Iteration   1: 9.411 ops/ms
Iteration   2: 9.264 ops/ms
Iteration   3: 9.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.327 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (9.264, 9.327, 9.411), stdev = 0.076
  CI (99.9%): [7.940, 10.713] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.917 ops/ms
# Warmup Iteration   2: 7.199 ops/ms
# Warmup Iteration   3: 7.867 ops/ms
Iteration   1: 7.982 ops/ms
Iteration   2: 7.836 ops/ms
Iteration   3: 7.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.859 ±(99.9%) 2.067 ops/ms [Average]
  (min, avg, max) = (7.759, 7.859, 7.982), stdev = 0.113
  CI (99.9%): [5.792, 9.926] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.349 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.004 ms/op
Iteration   1: 3.507 ±(99.9%) 0.004 ms/op
Iteration   2: 3.579 ±(99.9%) 0.003 ms/op
Iteration   3: 3.458 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.515 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (3.458, 3.515, 3.579), stdev = 0.061
  CI (99.9%): [2.401, 4.629] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.003 ms/op
Iteration   1: 3.364 ±(99.9%) 0.004 ms/op
Iteration   2: 3.407 ±(99.9%) 0.002 ms/op
Iteration   3: 3.346 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.372 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.346, 3.372, 3.407), stdev = 0.031
  CI (99.9%): [2.804, 3.940] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.823 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.004 ms/op
Iteration   1: 3.501 ±(99.9%) 0.003 ms/op
Iteration   2: 3.441 ±(99.9%) 0.003 ms/op
Iteration   3: 3.468 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.470 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (3.441, 3.470, 3.501), stdev = 0.030
  CI (99.9%): [2.919, 4.022] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.087 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.008 ms/op
Iteration   1: 4.188 ±(99.9%) 0.005 ms/op
Iteration   2: 4.107 ±(99.9%) 0.007 ms/op
Iteration   3: 4.172 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.156 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (4.107, 4.156, 4.188), stdev = 0.043
  CI (99.9%): [3.378, 4.934] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.515 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
Iteration   1: 3.398 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  17.382 ms/op
                 createUser·p0.9999: 21.056 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   2: 3.524 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  21.472 ms/op
                 createUser·p0.9999: 34.603 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   3: 3.565 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  19.802 ms/op
                 createUser·p0.9999: 23.889 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274677
  mean =      3.494 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4518 
    [ 2.500,  5.000) = 265546 
    [ 5.000,  7.500) = 3523 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     18.042 ms/op
     p(99.9900) =     31.365 ms/op
     p(99.9990) =     35.340 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.720 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.008 ms/op
Iteration   1: 3.403 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  13.206 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.409 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  20.649 ms/op
                 existUser·p0.9999: 24.170 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.411 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  22.347 ms/op
                 existUser·p0.9999: 25.907 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281568
  mean =      3.408 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7279 
    [ 2.500,  5.000) = 269473 
    [ 5.000,  7.500) = 3967 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     13.294 ms/op
     p(99.9900) =     24.790 ms/op
     p(99.9990) =     26.638 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.735 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.011 ms/op
Iteration   1: 3.622 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  18.998 ms/op
                 getUser·p0.9999: 22.796 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   2: 3.514 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  21.825 ms/op
                 getUser·p0.9999: 24.769 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 3.491 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  17.743 ms/op
                 getUser·p0.9999: 26.051 ms/op
                 getUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270806
  mean =      3.542 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1673 
    [ 2.500,  5.000) = 261694 
    [ 5.000,  7.500) = 6137 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     24.737 ms/op
     p(99.9990) =     26.842 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.260 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.013 ms/op
Iteration   1: 4.236 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.777 ms/op
                 listUser·p0.999:  19.174 ms/op
                 listUser·p0.9999: 22.166 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   2: 4.101 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.042 ms/op
                 listUser·p0.9999: 16.518 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.045 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 18.930 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232509
  mean =      4.126 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 225169 
    [ 5.000,  7.500) = 5488 
    [ 7.500, 10.000) = 1059 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 349 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     21.324 ms/op
     p(99.9990) =     22.337 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.098 ± 4.492  ops/ms
ClientPb.existUser                       thrpt       3   9.669 ± 1.011  ops/ms
ClientPb.getUser                         thrpt       3   9.327 ± 1.387  ops/ms
ClientPb.listUser                        thrpt       3   7.859 ± 2.067  ops/ms
ClientPb.createUser                       avgt       3   3.515 ± 1.114   ms/op
ClientPb.existUser                        avgt       3   3.372 ± 0.568   ms/op
ClientPb.getUser                          avgt       3   3.470 ± 0.551   ms/op
ClientPb.listUser                         avgt       3   4.156 ± 0.778   ms/op
ClientPb.createUser                     sample  274677   3.494 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.033           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.042           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.365           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  281568   3.408 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.053           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.294           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.790           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  270806   3.542 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.701           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.547           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.737           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.001           ms/op
ClientPb.listUser                       sample  232509   4.126 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.153           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.324           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.446           ms/op
