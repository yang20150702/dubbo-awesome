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
# Warmup Iteration   1: 1.932 ops/ms
# Warmup Iteration   2: 4.845 ops/ms
# Warmup Iteration   3: 8.494 ops/ms
Iteration   1: 9.014 ops/ms
Iteration   2: 9.431 ops/ms
Iteration   3: 9.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.335 ±(99.9%) 5.208 ops/ms [Average]
  (min, avg, max) = (9.014, 9.335, 9.561), stdev = 0.285
  CI (99.9%): [4.128, 14.543] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.955 ops/ms
# Warmup Iteration   2: 8.565 ops/ms
# Warmup Iteration   3: 9.328 ops/ms
Iteration   1: 9.611 ops/ms
Iteration   2: 9.845 ops/ms
Iteration   3: 9.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.753 ±(99.9%) 2.271 ops/ms [Average]
  (min, avg, max) = (9.611, 9.753, 9.845), stdev = 0.124
  CI (99.9%): [7.482, 12.024] (assumes normal distribution)


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
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 8.233 ops/ms
# Warmup Iteration   3: 9.083 ops/ms
Iteration   1: 9.071 ops/ms
Iteration   2: 8.945 ops/ms
Iteration   3: 9.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.138 ±(99.9%) 4.269 ops/ms [Average]
  (min, avg, max) = (8.945, 9.138, 9.398), stdev = 0.234
  CI (99.9%): [4.869, 13.407] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.544 ops/ms
# Warmup Iteration   2: 7.267 ops/ms
# Warmup Iteration   3: 7.808 ops/ms
Iteration   1: 7.575 ops/ms
Iteration   2: 7.864 ops/ms
Iteration   3: 7.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.778 ±(99.9%) 3.224 ops/ms [Average]
  (min, avg, max) = (7.575, 7.778, 7.895), stdev = 0.177
  CI (99.9%): [4.554, 11.002] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.521 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.005 ms/op
Iteration   1: 3.328 ±(99.9%) 0.006 ms/op
Iteration   2: 3.460 ±(99.9%) 0.006 ms/op
Iteration   3: 3.397 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.395 ±(99.9%) 1.207 ms/op [Average]
  (min, avg, max) = (3.328, 3.395, 3.460), stdev = 0.066
  CI (99.9%): [2.188, 4.602] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.399 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.008 ms/op
Iteration   1: 3.325 ±(99.9%) 0.003 ms/op
Iteration   2: 3.256 ±(99.9%) 0.010 ms/op
Iteration   3: 3.440 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.340 ±(99.9%) 1.699 ms/op [Average]
  (min, avg, max) = (3.256, 3.340, 3.440), stdev = 0.093
  CI (99.9%): [1.642, 5.039] (assumes normal distribution)


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
# Warmup Iteration   1: 11.407 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.003 ms/op
Iteration   1: 3.408 ±(99.9%) 0.008 ms/op
Iteration   2: 3.546 ±(99.9%) 0.006 ms/op
Iteration   3: 3.496 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.484 ±(99.9%) 1.270 ms/op [Average]
  (min, avg, max) = (3.408, 3.484, 3.546), stdev = 0.070
  CI (99.9%): [2.214, 4.753] (assumes normal distribution)


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
# Warmup Iteration   1: 11.256 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.265 ±(99.9%) 0.006 ms/op
Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
Iteration   2: 4.047 ±(99.9%) 0.013 ms/op
Iteration   3: 4.196 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.123 ±(99.9%) 1.353 ms/op [Average]
  (min, avg, max) = (4.047, 4.123, 4.196), stdev = 0.074
  CI (99.9%): [2.770, 5.477] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.472 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.015 ms/op
Iteration   1: 3.569 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  21.113 ms/op
                 createUser·p0.9999: 23.561 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.571 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.926 ms/op
                 createUser·p0.999:  22.556 ms/op
                 createUser·p0.9999: 25.430 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 3.450 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  18.381 ms/op
                 createUser·p0.9999: 26.697 ms/op
                 createUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272014
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5477 
    [ 2.500,  5.000) = 259727 
    [ 5.000,  7.500) = 5404 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     20.708 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     27.313 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 10.097 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.008 ms/op
Iteration   1: 3.394 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  20.863 ms/op
                 existUser·p0.9999: 25.185 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  21.715 ms/op
                 existUser·p0.9999: 26.840 ms/op
                 existUser·p1.00:   33.489 ms/op

Iteration   3: 3.371 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  17.102 ms/op
                 existUser·p0.9999: 27.986 ms/op
                 existUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282229
  mean =      3.398 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2060 
    [ 2.500,  5.000) = 274299 
    [ 5.000,  7.500) = 4695 
    [ 7.500, 10.000) = 616 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     17.851 ms/op
     p(99.9900) =     27.037 ms/op
     p(99.9990) =     33.166 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 10.170 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.013 ms/op
Iteration   1: 3.634 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  20.080 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.699 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  22.832 ms/op
                 getUser·p0.9999: 25.178 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.453 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  18.861 ms/op
                 getUser·p0.9999: 26.339 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267098
  mean =      3.592 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4831 
    [ 2.500,  5.000) = 251271 
    [ 5.000,  7.500) = 8597 
    [ 7.500, 10.000) = 1924 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     19.753 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 10.468 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
Iteration   1: 4.147 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   8.120 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 4.059 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  15.884 ms/op
                 listUser·p0.9999: 18.722 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.046 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.489 ms/op
                 listUser·p0.999:  15.545 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235184
  mean =      4.084 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 224001 
    [ 5.000,  7.500) = 8545 
    [ 7.500, 10.000) = 2004 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.913 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.710 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     22.493 ms/op
     p(99.9990) =     24.717 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.335 ± 5.208  ops/ms
ClientPb.existUser                       thrpt       3   9.753 ± 2.271  ops/ms
ClientPb.getUser                         thrpt       3   9.138 ± 4.269  ops/ms
ClientPb.listUser                        thrpt       3   7.778 ± 3.224  ops/ms
ClientPb.createUser                       avgt       3   3.395 ± 1.207   ms/op
ClientPb.existUser                        avgt       3   3.340 ± 1.699   ms/op
ClientPb.getUser                          avgt       3   3.484 ± 1.270   ms/op
ClientPb.listUser                         avgt       3   4.123 ± 1.353   ms/op
ClientPb.createUser                     sample  272014   3.529 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.497           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.554           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.708           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.887           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.591           ms/op
ClientPb.existUser                      sample  282229   3.398 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.262           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.046           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.851           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.037           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.489           ms/op
ClientPb.getUser                        sample  267098   3.592 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.457           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.389           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.753           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.297           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.361           ms/op
ClientPb.listUser                       sample  235184   4.084 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.913           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.710           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.187           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.493           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
