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
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 4.883 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 8.988 ops/ms
Iteration   2: 9.134 ops/ms
Iteration   3: 9.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.192 ±(99.9%) 4.329 ops/ms [Average]
  (min, avg, max) = (8.988, 9.192, 9.452), stdev = 0.237
  CI (99.9%): [4.863, 13.520] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.779 ops/ms
# Warmup Iteration   2: 8.177 ops/ms
# Warmup Iteration   3: 9.617 ops/ms
Iteration   1: 9.837 ops/ms
Iteration   2: 9.919 ops/ms
Iteration   3: 9.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.719 ±(99.9%) 5.072 ops/ms [Average]
  (min, avg, max) = (9.402, 9.719, 9.919), stdev = 0.278
  CI (99.9%): [4.648, 14.791] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.527 ops/ms
# Warmup Iteration   2: 7.644 ops/ms
# Warmup Iteration   3: 8.695 ops/ms
Iteration   1: 9.045 ops/ms
Iteration   2: 9.021 ops/ms
Iteration   3: 9.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.075 ±(99.9%) 1.354 ops/ms [Average]
  (min, avg, max) = (9.021, 9.075, 9.160), stdev = 0.074
  CI (99.9%): [7.722, 10.429] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 7.039 ops/ms
# Warmup Iteration   3: 7.715 ops/ms
Iteration   1: 7.678 ops/ms
Iteration   2: 7.511 ops/ms
Iteration   3: 7.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.661 ±(99.9%) 2.590 ops/ms [Average]
  (min, avg, max) = (7.511, 7.661, 7.794), stdev = 0.142
  CI (99.9%): [5.071, 10.251] (assumes normal distribution)


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
# Warmup Iteration   1: 9.960 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.004 ms/op
Iteration   1: 3.521 ±(99.9%) 0.007 ms/op
Iteration   2: 3.533 ±(99.9%) 0.011 ms/op
Iteration   3: 3.487 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.514 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.487, 3.514, 3.533), stdev = 0.024
  CI (99.9%): [3.076, 3.951] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.173 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.006 ms/op
Iteration   1: 3.281 ±(99.9%) 0.009 ms/op
Iteration   2: 3.260 ±(99.9%) 0.004 ms/op
Iteration   3: 3.434 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.325 ±(99.9%) 1.730 ms/op [Average]
  (min, avg, max) = (3.260, 3.325, 3.434), stdev = 0.095
  CI (99.9%): [1.595, 5.055] (assumes normal distribution)


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
# Warmup Iteration   1: 10.136 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.008 ms/op
Iteration   1: 3.666 ±(99.9%) 0.005 ms/op
Iteration   2: 3.386 ±(99.9%) 0.010 ms/op
Iteration   3: 3.424 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.492 ±(99.9%) 2.776 ms/op [Average]
  (min, avg, max) = (3.386, 3.492, 3.666), stdev = 0.152
  CI (99.9%): [0.716, 6.268] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.098 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.573 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.006 ms/op
Iteration   1: 4.069 ±(99.9%) 0.010 ms/op
Iteration   2: 4.183 ±(99.9%) 0.006 ms/op
Iteration   3: 4.003 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.085 ±(99.9%) 1.659 ms/op [Average]
  (min, avg, max) = (4.003, 4.085, 4.183), stdev = 0.091
  CI (99.9%): [2.426, 5.744] (assumes normal distribution)


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
# Warmup Iteration   1: 10.465 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.018 ms/op
Iteration   1: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  23.471 ms/op
                 createUser·p0.9999: 28.230 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 3.470 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  25.554 ms/op
                 createUser·p0.9999: 31.261 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   3: 3.561 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  23.272 ms/op
                 createUser·p0.9999: 32.310 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275603
  mean =      3.481 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5024 
    [ 2.500,  5.000) = 264406 
    [ 5.000,  7.500) = 5093 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.567 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     23.521 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     32.661 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 8.624 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.010 ms/op
Iteration   1: 3.299 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  11.628 ms/op
                 existUser·p0.9999: 26.572 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.926 ms/op
                 existUser·p0.99:   5.961 ms/op
                 existUser·p0.999:  11.988 ms/op
                 existUser·p0.9999: 33.173 ms/op
                 existUser·p1.00:   33.751 ms/op

Iteration   3: 3.259 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 32.656 ms/op
                 existUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291336
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6607 
    [ 2.500,  5.000) = 278737 
    [ 5.000,  7.500) = 5080 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     32.534 ms/op
     p(99.9990) =     33.566 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 9.261 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.011 ms/op
Iteration   1: 3.397 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  22.936 ms/op
                 getUser·p0.9999: 26.182 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   2: 3.428 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  24.365 ms/op
                 getUser·p0.9999: 30.267 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 3.573 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  22.340 ms/op
                 getUser·p0.9999: 29.196 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276728
  mean =      3.464 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5014 
    [ 2.500,  5.000) = 263833 
    [ 5.000,  7.500) = 6773 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     22.833 ms/op
     p(99.9900) =     29.338 ms/op
     p(99.9990) =     30.676 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 11.786 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.016 ms/op
Iteration   1: 4.128 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.639 ms/op
                 listUser·p0.999:  22.151 ms/op
                 listUser·p0.9999: 28.189 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   2: 4.107 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 4.061 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.305 ms/op
                 listUser·p0.999:  16.542 ms/op
                 listUser·p0.9999: 18.387 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234126
  mean =      4.099 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 224373 
    [ 5.000,  7.500) = 7345 
    [ 7.500, 10.000) = 1548 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     25.767 ms/op
     p(99.9990) =     29.185 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.192 ± 4.329  ops/ms
ClientPb.existUser                       thrpt       3   9.719 ± 5.072  ops/ms
ClientPb.getUser                         thrpt       3   9.075 ± 1.354  ops/ms
ClientPb.listUser                        thrpt       3   7.661 ± 2.590  ops/ms
ClientPb.createUser                       avgt       3   3.514 ± 0.438   ms/op
ClientPb.existUser                        avgt       3   3.325 ± 1.730   ms/op
ClientPb.getUser                          avgt       3   3.492 ± 2.776   ms/op
ClientPb.listUser                         avgt       3   4.085 ± 1.659   ms/op
ClientPb.createUser                     sample  275603   3.481 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.567           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.521           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.392           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.030           ms/op
ClientPb.existUser                      sample  291336   3.292 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.364           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.059           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.534           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  276728   3.464 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.833           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.338           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  234126   4.099 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.596           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.767           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.196           ms/op
