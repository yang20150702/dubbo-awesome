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
# Warmup Iteration   1: 2.056 ops/ms
# Warmup Iteration   2: 5.007 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 9.021 ops/ms
Iteration   2: 9.355 ops/ms
Iteration   3: 9.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.183 ±(99.9%) 3.055 ops/ms [Average]
  (min, avg, max) = (9.021, 9.183, 9.355), stdev = 0.167
  CI (99.9%): [6.128, 12.238] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.921 ops/ms
# Warmup Iteration   2: 8.614 ops/ms
# Warmup Iteration   3: 9.486 ops/ms
Iteration   1: 9.509 ops/ms
Iteration   2: 9.528 ops/ms
Iteration   3: 9.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.392 ±(99.9%) 4.006 ops/ms [Average]
  (min, avg, max) = (9.139, 9.392, 9.528), stdev = 0.220
  CI (99.9%): [5.386, 13.398] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.388 ops/ms
# Warmup Iteration   2: 8.342 ops/ms
# Warmup Iteration   3: 8.934 ops/ms
Iteration   1: 9.408 ops/ms
Iteration   2: 9.342 ops/ms
Iteration   3: 9.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.336 ±(99.9%) 1.377 ops/ms [Average]
  (min, avg, max) = (9.257, 9.336, 9.408), stdev = 0.076
  CI (99.9%): [7.958, 10.713] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.447 ops/ms
# Warmup Iteration   2: 6.867 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 7.855 ops/ms
Iteration   2: 7.836 ops/ms
Iteration   3: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.904 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (7.836, 7.904, 8.022), stdev = 0.102
  CI (99.9%): [6.037, 9.771] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.567 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.009 ms/op
Iteration   1: 3.430 ±(99.9%) 0.005 ms/op
Iteration   2: 3.573 ±(99.9%) 0.004 ms/op
Iteration   3: 3.298 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.434 ±(99.9%) 2.514 ms/op [Average]
  (min, avg, max) = (3.298, 3.434, 3.573), stdev = 0.138
  CI (99.9%): [0.920, 5.947] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.122 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.005 ms/op
Iteration   1: 3.254 ±(99.9%) 0.010 ms/op
Iteration   2: 3.308 ±(99.9%) 0.004 ms/op
Iteration   3: 3.241 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.267 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (3.241, 3.267, 3.308), stdev = 0.035
  CI (99.9%): [2.623, 3.912] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.805 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.005 ms/op
Iteration   1: 3.405 ±(99.9%) 0.005 ms/op
Iteration   2: 3.318 ±(99.9%) 0.007 ms/op
Iteration   3: 3.283 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.335 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (3.283, 3.335, 3.405), stdev = 0.063
  CI (99.9%): [2.188, 4.483] (assumes normal distribution)


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
# Warmup Iteration   1: 10.025 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.009 ms/op
Iteration   1: 4.107 ±(99.9%) 0.005 ms/op
Iteration   2: 4.000 ±(99.9%) 0.012 ms/op
Iteration   3: 3.944 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.017 ±(99.9%) 1.514 ms/op [Average]
  (min, avg, max) = (3.944, 4.017, 4.107), stdev = 0.083
  CI (99.9%): [2.503, 5.532] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.977 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.011 ms/op
Iteration   1: 3.443 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  20.970 ms/op
                 createUser·p0.9999: 23.344 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.569 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 25.364 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.549 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  20.167 ms/op
                 createUser·p0.9999: 27.361 ms/op
                 createUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272752
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9676 
    [ 2.500,  5.000) = 254785 
    [ 5.000,  7.500) = 7020 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     26.042 ms/op
     p(99.9990) =     27.662 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.047 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
Iteration   1: 3.417 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  19.572 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 26.304 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  23.008 ms/op
                 existUser·p0.9999: 29.745 ms/op
                 existUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280929
  mean =      3.415 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13359 
    [ 2.500,  5.000) = 260936 
    [ 5.000,  7.500) = 5665 
    [ 7.500, 10.000) = 616 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     11.519 ms/op
     p(99.9900) =     28.535 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 11.487 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.011 ms/op
Iteration   1: 3.446 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  18.487 ms/op
                 getUser·p0.9999: 24.665 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.400 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.849 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  20.221 ms/op
                 getUser·p0.9999: 25.415 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   3: 3.600 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  19.995 ms/op
                 getUser·p0.9999: 25.923 ms/op
                 getUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275685
  mean =      3.480 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8007 
    [ 2.500,  5.000) = 258780 
    [ 5.000,  7.500) = 7817 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     19.376 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     26.329 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 10.942 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.015 ms/op
Iteration   1: 4.133 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.929 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  21.909 ms/op
                 listUser·p0.9999: 27.534 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  15.810 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.295 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236954
  mean =      4.050 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 226947 
    [ 5.000,  7.500) = 7317 
    [ 7.500, 10.000) = 1770 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     26.169 ms/op
     p(99.9990) =     27.644 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.183 ± 3.055  ops/ms
ClientPb.existUser                       thrpt       3   9.392 ± 4.006  ops/ms
ClientPb.getUser                         thrpt       3   9.336 ± 1.377  ops/ms
ClientPb.listUser                        thrpt       3   7.904 ± 1.867  ops/ms
ClientPb.createUser                       avgt       3   3.434 ± 2.514   ms/op
ClientPb.existUser                        avgt       3   3.267 ± 0.645   ms/op
ClientPb.getUser                          avgt       3   3.335 ± 1.148   ms/op
ClientPb.listUser                         avgt       3   4.017 ± 1.514   ms/op
ClientPb.createUser                     sample  272752   3.519 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.544           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.275           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.155           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.042           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.344           ms/op
ClientPb.existUser                      sample  280929   3.415 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.155           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.087           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.519           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.535           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.933           ms/op
ClientPb.getUser                        sample  275685   3.480 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.114           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.376           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.494           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.411           ms/op
ClientPb.listUser                       sample  236954   4.050 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.859           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.169           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.377           ms/op
