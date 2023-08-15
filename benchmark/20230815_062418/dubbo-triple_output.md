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
# Warmup Iteration   1: 2.286 ops/ms
# Warmup Iteration   2: 5.064 ops/ms
# Warmup Iteration   3: 8.418 ops/ms
Iteration   1: 8.846 ops/ms
Iteration   2: 9.004 ops/ms
Iteration   3: 9.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.040 ±(99.9%) 3.909 ops/ms [Average]
  (min, avg, max) = (8.846, 9.040, 9.270), stdev = 0.214
  CI (99.9%): [5.131, 12.949] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.887 ops/ms
# Warmup Iteration   2: 8.475 ops/ms
# Warmup Iteration   3: 9.268 ops/ms
Iteration   1: 9.741 ops/ms
Iteration   2: 9.672 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.613 ±(99.9%) 3.016 ops/ms [Average]
  (min, avg, max) = (9.427, 9.613, 9.741), stdev = 0.165
  CI (99.9%): [6.598, 12.629] (assumes normal distribution)


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
# Warmup Iteration   1: 3.046 ops/ms
# Warmup Iteration   2: 8.466 ops/ms
# Warmup Iteration   3: 8.773 ops/ms
Iteration   1: 9.094 ops/ms
Iteration   2: 9.302 ops/ms
Iteration   3: 9.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.196 ±(99.9%) 1.900 ops/ms [Average]
  (min, avg, max) = (9.094, 9.196, 9.302), stdev = 0.104
  CI (99.9%): [7.296, 11.095] (assumes normal distribution)


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
# Warmup Iteration   1: 2.922 ops/ms
# Warmup Iteration   2: 7.066 ops/ms
# Warmup Iteration   3: 7.756 ops/ms
Iteration   1: 7.770 ops/ms
Iteration   2: 7.905 ops/ms
Iteration   3: 7.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.890 ±(99.9%) 2.063 ops/ms [Average]
  (min, avg, max) = (7.770, 7.890, 7.995), stdev = 0.113
  CI (99.9%): [5.826, 9.953] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.353 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.005 ms/op
Iteration   1: 3.436 ±(99.9%) 0.005 ms/op
Iteration   2: 3.561 ±(99.9%) 0.005 ms/op
Iteration   3: 3.434 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.477 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (3.434, 3.477, 3.561), stdev = 0.073
  CI (99.9%): [2.149, 4.805] (assumes normal distribution)


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
# Warmup Iteration   1: 9.264 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.003 ms/op
Iteration   1: 3.407 ±(99.9%) 0.004 ms/op
Iteration   2: 3.402 ±(99.9%) 0.003 ms/op
Iteration   3: 3.265 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.358 ±(99.9%) 1.472 ms/op [Average]
  (min, avg, max) = (3.265, 3.358, 3.407), stdev = 0.081
  CI (99.9%): [1.886, 4.830] (assumes normal distribution)


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
# Warmup Iteration   1: 10.706 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.007 ms/op
Iteration   1: 3.464 ±(99.9%) 0.004 ms/op
Iteration   2: 3.469 ±(99.9%) 0.007 ms/op
Iteration   3: 3.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.496 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.464, 3.496, 3.554), stdev = 0.050
  CI (99.9%): [2.578, 4.414] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.853 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.007 ms/op
Iteration   1: 4.010 ±(99.9%) 0.009 ms/op
Iteration   2: 3.901 ±(99.9%) 0.014 ms/op
Iteration   3: 4.137 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.016 ±(99.9%) 2.163 ms/op [Average]
  (min, avg, max) = (3.901, 4.016, 4.137), stdev = 0.119
  CI (99.9%): [1.853, 6.180] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.923 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.009 ms/op
Iteration   1: 3.363 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.655 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.765 ms/op
                 createUser·p0.999:  16.201 ms/op
                 createUser·p0.9999: 20.068 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.412 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   6.260 ms/op
                 createUser·p0.999:  17.574 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.536 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.817 ms/op
                 createUser·p0.999:  21.660 ms/op
                 createUser·p0.9999: 24.542 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279102
  mean =      3.435 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6247 
    [ 2.500,  5.000) = 267855 
    [ 5.000,  7.500) = 3643 
    [ 7.500, 10.000) = 981 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     17.298 ms/op
     p(99.9900) =     23.632 ms/op
     p(99.9990) =     27.401 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 9.197 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.009 ms/op
Iteration   1: 3.381 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  19.891 ms/op
                 existUser·p0.9999: 23.414 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   2: 3.372 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.979 ms/op
                 existUser·p0.999:  22.282 ms/op
                 existUser·p0.9999: 24.936 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   3: 3.461 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  20.238 ms/op
                 existUser·p0.9999: 28.500 ms/op
                 existUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281793
  mean =      3.404 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9936 
    [ 2.500,  5.000) = 263553 
    [ 5.000,  7.500) = 6459 
    [ 7.500, 10.000) = 1233 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     29.864 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 9.500 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.011 ms/op
Iteration   1: 3.545 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  20.537 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 28.749 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 3.514 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.574 ms/op
                 getUser·p0.999:  18.774 ms/op
                 getUser·p0.9999: 28.734 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274463
  mean =      3.495 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10825 
    [ 2.500,  5.000) = 253410 
    [ 5.000,  7.500) = 8409 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     19.721 ms/op
     p(99.9900) =     28.548 ms/op
     p(99.9990) =     29.410 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 11.467 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.677 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.014 ms/op
Iteration   1: 4.067 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.944 ms/op
                 listUser·p0.999:  17.713 ms/op
                 listUser·p0.9999: 22.569 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.691 ms/op
                 listUser·p0.999:  16.630 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   8.259 ms/op
                 listUser·p0.999:  16.677 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236078
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 225594 
    [ 5.000,  7.500) = 7423 
    [ 7.500, 10.000) = 2044 
    [10.000, 12.500) = 426 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     21.771 ms/op
     p(99.9990) =     24.573 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.040 ± 3.909  ops/ms
ClientPb.existUser                       thrpt       3   9.613 ± 3.016  ops/ms
ClientPb.getUser                         thrpt       3   9.196 ± 1.900  ops/ms
ClientPb.listUser                        thrpt       3   7.890 ± 2.063  ops/ms
ClientPb.createUser                       avgt       3   3.477 ± 1.328   ms/op
ClientPb.existUser                        avgt       3   3.358 ± 1.472   ms/op
ClientPb.getUser                          avgt       3   3.496 ± 0.918   ms/op
ClientPb.listUser                         avgt       3   4.016 ± 2.163   ms/op
ClientPb.createUser                     sample  279102   3.435 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.824           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.632           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.787           ms/op
ClientPb.existUser                      sample  281793   3.404 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.307           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.087           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.935           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.179           ms/op
ClientPb.getUser                        sample  274463   3.495 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.758           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.721           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.548           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  236078   4.063 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.777           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.771           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.164           ms/op
