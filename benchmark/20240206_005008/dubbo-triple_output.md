# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ops/ms
# Warmup Iteration   2: 12.260 ops/ms
# Warmup Iteration   3: 12.437 ops/ms
Iteration   1: 12.549 ops/ms
Iteration   2: 12.610 ops/ms
Iteration   3: 12.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.540 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (12.461, 12.540, 12.610), stdev = 0.075
  CI (99.9%): [11.169, 13.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.381 ops/ms
# Warmup Iteration   2: 13.185 ops/ms
# Warmup Iteration   3: 13.113 ops/ms
Iteration   1: 13.157 ops/ms
Iteration   2: 13.139 ops/ms
Iteration   3: 13.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.115 ±(99.9%) 1.053 ops/ms [Average]
  (min, avg, max) = (13.049, 13.115, 13.157), stdev = 0.058
  CI (99.9%): [12.062, 14.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.015 ops/ms
# Warmup Iteration   2: 12.672 ops/ms
# Warmup Iteration   3: 12.771 ops/ms
Iteration   1: 12.616 ops/ms
Iteration   2: 12.823 ops/ms
Iteration   3: 13.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.821 ±(99.9%) 3.726 ops/ms [Average]
  (min, avg, max) = (12.616, 12.821, 13.024), stdev = 0.204
  CI (99.9%): [9.095, 16.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.543 ops/ms
# Warmup Iteration   2: 10.440 ops/ms
# Warmup Iteration   3: 10.383 ops/ms
Iteration   1: 10.454 ops/ms
Iteration   2: 10.479 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.464 ±(99.9%) 0.237 ops/ms [Average]
  (min, avg, max) = (10.454, 10.464, 10.479), stdev = 0.013
  CI (99.9%): [10.227, 10.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.004 ms/op
Iteration   1: 2.553 ±(99.9%) 0.005 ms/op
Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
Iteration   3: 2.553 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.543, 2.550, 2.553), stdev = 0.006
  CI (99.9%): [2.443, 2.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
Iteration   3: 2.456 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.446, 2.450, 2.456), stdev = 0.005
  CI (99.9%): [2.355, 2.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
Iteration   3: 2.516 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.507 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.496, 2.507, 2.516), stdev = 0.010
  CI (99.9%): [2.324, 2.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.957 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
Iteration   3: 3.039 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.029 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (3.021, 3.029, 3.039), stdev = 0.009
  CI (99.9%): [2.865, 3.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  7.554 ms/op
                 createUser·p0.9999: 12.945 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.680 ms/op
                 createUser·p0.999:  9.838 ms/op
                 createUser·p0.9999: 12.344 ms/op
                 createUser·p1.00:   13.304 ms/op

Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   4.043 ms/op
                 createUser·p0.999:  9.333 ms/op
                 createUser·p0.9999: 10.842 ms/op
                 createUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380573
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 184572 
    [ 2.500,  3.750) = 191962 
    [ 3.750,  5.000) = 3073 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     12.632 ms/op
     p(99.9990) =     13.304 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  9.403 ms/op
                 existUser·p0.9999: 14.255 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  7.164 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  6.391 ms/op
                 existUser·p0.9999: 12.063 ms/op
                 existUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385857
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 188273 
    [ 2.500,  3.750) = 194010 
    [ 3.750,  5.000) = 2816 
    [ 5.000,  6.250) = 284 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.723 ms/op
     p(99.9900) =     13.294 ms/op
     p(99.9990) =     15.328 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  11.992 ms/op
                 getUser·p0.9999: 13.934 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  8.605 ms/op
                 getUser·p0.9999: 12.213 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  7.024 ms/op
                 getUser·p0.9999: 13.091 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384781
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 189908 
    [ 2.500,  3.750) = 189513 
    [ 3.750,  5.000) = 4119 
    [ 5.000,  6.250) = 722 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      7.730 ms/op
     p(99.9900) =     13.558 ms/op
     p(99.9990) =     14.100 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.598 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  10.092 ms/op
                 listUser·p0.9999: 12.845 ms/op
                 listUser·p1.00:   13.599 ms/op

Iteration   2: 3.084 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.754 ms/op
                 listUser·p0.9999: 11.801 ms/op
                 listUser·p1.00:   12.485 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  8.777 ms/op
                 listUser·p0.9999: 12.648 ms/op
                 listUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314015
  mean =      3.055 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 83850 
    [ 2.500,  3.750) = 187998 
    [ 3.750,  5.000) = 34761 
    [ 5.000,  6.250) = 5800 
    [ 6.250,  7.500) = 677 
    [ 7.500,  8.750) = 265 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     12.468 ms/op
     p(99.9990) =     13.227 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.540 ± 1.371  ops/ms
ClientPb.existUser                       thrpt       3  13.115 ± 1.053  ops/ms
ClientPb.getUser                         thrpt       3  12.821 ± 3.726  ops/ms
ClientPb.listUser                        thrpt       3  10.464 ± 0.237  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.107   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.096   ms/op
ClientPb.getUser                          avgt       3   2.507 ± 0.183   ms/op
ClientPb.listUser                         avgt       3   3.029 ± 0.164   ms/op
ClientPb.createUser                     sample  380573   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.919           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.355           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.632           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.337           ms/op
ClientPb.existUser                      sample  385857   2.486 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.723           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.294           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.417           ms/op
ClientPb.getUser                        sample  384781   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.954           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.730           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.558           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.352           ms/op
ClientPb.listUser                       sample  314015   3.055 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.598           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.468           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.599           ms/op
