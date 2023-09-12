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
# Warmup Iteration   1: 1.905 ops/ms
# Warmup Iteration   2: 4.930 ops/ms
# Warmup Iteration   3: 8.563 ops/ms
Iteration   1: 9.153 ops/ms
Iteration   2: 8.910 ops/ms
Iteration   3: 9.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.112 ±(99.9%) 3.375 ops/ms [Average]
  (min, avg, max) = (8.910, 9.112, 9.273), stdev = 0.185
  CI (99.9%): [5.737, 12.487] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.083 ops/ms
# Warmup Iteration   2: 8.560 ops/ms
# Warmup Iteration   3: 9.528 ops/ms
Iteration   1: 9.589 ops/ms
Iteration   2: 9.565 ops/ms
Iteration   3: 9.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.582 ±(99.9%) 0.282 ops/ms [Average]
  (min, avg, max) = (9.565, 9.582, 9.593), stdev = 0.015
  CI (99.9%): [9.300, 9.864] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.861 ops/ms
# Warmup Iteration   2: 8.476 ops/ms
# Warmup Iteration   3: 8.551 ops/ms
Iteration   1: 9.293 ops/ms
Iteration   2: 9.057 ops/ms
Iteration   3: 9.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.234 ±(99.9%) 2.857 ops/ms [Average]
  (min, avg, max) = (9.057, 9.234, 9.353), stdev = 0.157
  CI (99.9%): [6.377, 12.091] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 7.244 ops/ms
# Warmup Iteration   3: 7.428 ops/ms
Iteration   1: 7.737 ops/ms
Iteration   2: 7.751 ops/ms
Iteration   3: 7.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.737 ±(99.9%) 0.249 ops/ms [Average]
  (min, avg, max) = (7.724, 7.737, 7.751), stdev = 0.014
  CI (99.9%): [7.488, 7.987] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.652 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.005 ms/op
Iteration   1: 3.590 ±(99.9%) 0.002 ms/op
Iteration   2: 3.655 ±(99.9%) 0.007 ms/op
Iteration   3: 3.490 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.578 ±(99.9%) 1.512 ms/op [Average]
  (min, avg, max) = (3.490, 3.578, 3.655), stdev = 0.083
  CI (99.9%): [2.066, 5.090] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.077 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.004 ms/op
Iteration   1: 3.378 ±(99.9%) 0.003 ms/op
Iteration   2: 3.328 ±(99.9%) 0.012 ms/op
Iteration   3: 3.363 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.356 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.328, 3.356, 3.378), stdev = 0.026
  CI (99.9%): [2.887, 3.825] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.722 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.006 ms/op
Iteration   1: 3.541 ±(99.9%) 0.005 ms/op
Iteration   2: 3.516 ±(99.9%) 0.002 ms/op
Iteration   3: 3.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.522 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.509, 3.522, 3.541), stdev = 0.017
  CI (99.9%): [3.217, 3.828] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.301 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.008 ms/op
Iteration   1: 4.111 ±(99.9%) 0.007 ms/op
Iteration   2: 4.041 ±(99.9%) 0.007 ms/op
Iteration   3: 3.995 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.049 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.995, 4.049, 4.111), stdev = 0.059
  CI (99.9%): [2.980, 5.118] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.424 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.011 ms/op
Iteration   1: 3.457 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.446 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  20.060 ms/op
                 createUser·p0.9999: 24.208 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.503 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.130 ms/op
                 createUser·p0.999:  22.339 ms/op
                 createUser·p0.9999: 28.373 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   3: 3.516 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  15.192 ms/op
                 createUser·p0.9999: 26.903 ms/op
                 createUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274668
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6744 
    [ 2.500,  5.000) = 260774 
    [ 5.000,  7.500) = 5384 
    [ 7.500, 10.000) = 1186 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     15.723 ms/op
     p(99.9900) =     27.510 ms/op
     p(99.9990) =     28.582 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.458 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
Iteration   1: 3.356 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  19.823 ms/op
                 existUser·p0.9999: 25.050 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 3.421 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  20.775 ms/op
                 existUser·p0.9999: 28.681 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   3: 3.451 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.359 ms/op
                 existUser·p0.999:  12.812 ms/op
                 existUser·p0.9999: 32.569 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281652
  mean =      3.409 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5914 
    [ 2.500,  5.000) = 268200 
    [ 5.000,  7.500) = 6115 
    [ 7.500, 10.000) = 1006 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     31.020 ms/op
     p(99.9990) =     33.513 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.910 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.012 ms/op
Iteration   1: 3.512 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  15.987 ms/op
                 getUser·p0.9999: 24.864 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 3.521 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  21.467 ms/op
                 getUser·p0.9999: 26.045 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 3.509 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  21.791 ms/op
                 getUser·p0.9999: 31.261 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273010
  mean =      3.514 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5599 
    [ 2.500,  5.000) = 257631 
    [ 5.000,  7.500) = 8062 
    [ 7.500, 10.000) = 1221 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 142 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     29.711 ms/op
     p(99.9990) =     32.244 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.814 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.014 ms/op
Iteration   1: 4.380 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  22.085 ms/op
                 listUser·p0.9999: 25.025 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  17.120 ms/op
                 listUser·p0.9999: 26.349 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   3: 4.132 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  14.691 ms/op
                 listUser·p0.9999: 17.900 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229188
  mean =      4.186 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 215662 
    [ 5.000,  7.500) = 10478 
    [ 7.500, 10.000) = 1939 
    [10.000, 12.500) = 522 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     17.263 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     26.500 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.112 ± 3.375  ops/ms
ClientPb.existUser                       thrpt       3   9.582 ± 0.282  ops/ms
ClientPb.getUser                         thrpt       3   9.234 ± 2.857  ops/ms
ClientPb.listUser                        thrpt       3   7.737 ± 0.249  ops/ms
ClientPb.createUser                       avgt       3   3.578 ± 1.512   ms/op
ClientPb.existUser                        avgt       3   3.356 ± 0.469   ms/op
ClientPb.getUser                          avgt       3   3.522 ± 0.306   ms/op
ClientPb.listUser                         avgt       3   4.049 ± 1.069   ms/op
ClientPb.createUser                     sample  274668   3.492 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.446           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.291           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.723           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.510           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.738           ms/op
ClientPb.existUser                      sample  281652   3.409 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.804           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.271           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.020           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  273010   3.514 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.321           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.384           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.711           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.670           ms/op
ClientPb.listUser                       sample  229188   4.186 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.887           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.979           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.263           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.592           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.542           ms/op
