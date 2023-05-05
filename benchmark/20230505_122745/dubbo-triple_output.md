# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 5.657 ops/ms
# Warmup Iteration   3: 8.679 ops/ms
Iteration   1: 9.345 ops/ms
Iteration   2: 9.243 ops/ms
Iteration   3: 9.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.384 ±(99.9%) 2.992 ops/ms [Average]
  (min, avg, max) = (9.243, 9.384, 9.564), stdev = 0.164
  CI (99.9%): [6.392, 12.376] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.748 ops/ms
# Warmup Iteration   2: 8.131 ops/ms
# Warmup Iteration   3: 9.011 ops/ms
Iteration   1: 9.335 ops/ms
Iteration   2: 9.731 ops/ms
Iteration   3: 9.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.547 ±(99.9%) 3.644 ops/ms [Average]
  (min, avg, max) = (9.335, 9.547, 9.731), stdev = 0.200
  CI (99.9%): [5.903, 13.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.865 ops/ms
# Warmup Iteration   2: 8.341 ops/ms
# Warmup Iteration   3: 9.054 ops/ms
Iteration   1: 8.937 ops/ms
Iteration   2: 9.410 ops/ms
Iteration   3: 9.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.222 ±(99.9%) 4.572 ops/ms [Average]
  (min, avg, max) = (8.937, 9.222, 9.410), stdev = 0.251
  CI (99.9%): [4.649, 13.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.679 ops/ms
# Warmup Iteration   2: 7.368 ops/ms
# Warmup Iteration   3: 7.922 ops/ms
Iteration   1: 7.922 ops/ms
Iteration   2: 7.924 ops/ms
Iteration   3: 8.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.002 ±(99.9%) 2.477 ops/ms [Average]
  (min, avg, max) = (7.922, 8.002, 8.158), stdev = 0.136
  CI (99.9%): [5.525, 10.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.054 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.008 ms/op
Iteration   1: 3.407 ±(99.9%) 0.008 ms/op
Iteration   2: 3.299 ±(99.9%) 0.014 ms/op
Iteration   3: 3.382 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.362 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (3.299, 3.362, 3.407), stdev = 0.057
  CI (99.9%): [2.326, 4.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.617 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.009 ms/op
Iteration   1: 3.265 ±(99.9%) 0.009 ms/op
Iteration   2: 3.440 ±(99.9%) 0.005 ms/op
Iteration   3: 3.257 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.321 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (3.257, 3.321, 3.440), stdev = 0.103
  CI (99.9%): [1.434, 5.207] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.977 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.005 ms/op
Iteration   1: 3.421 ±(99.9%) 0.003 ms/op
Iteration   2: 3.468 ±(99.9%) 0.005 ms/op
Iteration   3: 3.488 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.459 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (3.421, 3.459, 3.488), stdev = 0.034
  CI (99.9%): [2.833, 4.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.920 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.010 ms/op
Iteration   1: 3.979 ±(99.9%) 0.012 ms/op
Iteration   2: 4.026 ±(99.9%) 0.008 ms/op
Iteration   3: 4.001 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.002 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (3.979, 4.002, 4.026), stdev = 0.023
  CI (99.9%): [3.581, 4.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.227 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.010 ms/op
Iteration   1: 3.510 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  21.262 ms/op
                 createUser·p0.9999: 26.458 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   2: 3.479 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 27.551 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   3: 3.610 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  17.575 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271789
  mean =      3.532 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5832 
    [ 2.500,  5.000) = 258153 
    [ 5.000,  7.500) = 6844 
    [ 7.500, 10.000) = 600 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 98 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     26.963 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.440 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.009 ms/op
Iteration   1: 3.273 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  13.745 ms/op
                 existUser·p0.9999: 24.125 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.276 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 40.845 ms/op
                 existUser·p1.00:   42.271 ms/op

Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  18.678 ms/op
                 existUser·p0.9999: 24.629 ms/op
                 existUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289274
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 285310 
    [ 5.000, 10.000) = 3522 
    [10.000, 15.000) = 150 
    [15.000, 20.000) = 28 
    [20.000, 25.000) = 227 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     15.331 ms/op
     p(99.9900) =     39.916 ms/op
     p(99.9990) =     41.847 ms/op
     p(99.9999) =     42.271 ms/op
    p(100.0000) =     42.271 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.909 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.011 ms/op
Iteration   1: 3.538 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   7.391 ms/op
                 getUser·p0.999:  18.659 ms/op
                 getUser·p0.9999: 24.428 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.465 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  22.708 ms/op
                 getUser·p0.9999: 25.068 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   3: 3.574 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  18.341 ms/op
                 getUser·p0.9999: 30.022 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272309
  mean =      3.525 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4744 
    [ 2.500,  5.000) = 259271 
    [ 5.000,  7.500) = 6628 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 147 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     18.635 ms/op
     p(99.9900) =     27.928 ms/op
     p(99.9990) =     30.427 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.228 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.014 ms/op
Iteration   1: 4.130 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   8.363 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 29.386 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 4.067 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.233 ms/op
                 listUser·p0.9999: 17.478 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.342 ms/op
                 listUser·p0.999:  16.998 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234295
  mean =      4.094 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 223687 
    [ 5.000,  7.500) = 7206 
    [ 7.500, 10.000) = 2313 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     16.440 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     31.117 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.384 ± 2.992  ops/ms
ClientPb.existUser                       thrpt       3   9.547 ± 3.644  ops/ms
ClientPb.getUser                         thrpt       3   9.222 ± 4.572  ops/ms
ClientPb.listUser                        thrpt       3   8.002 ± 2.477  ops/ms
ClientPb.createUser                       avgt       3   3.362 ± 1.037   ms/op
ClientPb.existUser                        avgt       3   3.321 ± 1.886   ms/op
ClientPb.getUser                          avgt       3   3.459 ± 0.627   ms/op
ClientPb.listUser                         avgt       3   4.002 ± 0.421   ms/op
ClientPb.createUser                     sample  271789   3.532 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.524           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.218           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.354           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.963           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.377           ms/op
ClientPb.existUser                      sample  289274   3.316 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.343           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.331           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.916           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.271           ms/op
ClientPb.getUser                        sample  272309   3.525 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.518           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.635           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.928           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  234295   4.094 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.440           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.541           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.326           ms/op
