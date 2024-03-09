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
# Warmup Iteration   1: 5.145 ops/ms
# Warmup Iteration   2: 12.532 ops/ms
# Warmup Iteration   3: 12.740 ops/ms
Iteration   1: 12.948 ops/ms
Iteration   2: 12.927 ops/ms
Iteration   3: 12.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.943 ±(99.9%) 0.268 ops/ms [Average]
  (min, avg, max) = (12.927, 12.943, 12.955), stdev = 0.015
  CI (99.9%): [12.675, 13.211] (assumes normal distribution)


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
# Warmup Iteration   1: 8.510 ops/ms
# Warmup Iteration   2: 13.181 ops/ms
# Warmup Iteration   3: 13.464 ops/ms
Iteration   1: 13.474 ops/ms
Iteration   2: 13.398 ops/ms
Iteration   3: 13.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.373 ±(99.9%) 2.112 ops/ms [Average]
  (min, avg, max) = (13.247, 13.373, 13.474), stdev = 0.116
  CI (99.9%): [11.261, 15.485] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.438 ops/ms
# Warmup Iteration   2: 13.012 ops/ms
# Warmup Iteration   3: 13.149 ops/ms
Iteration   1: 13.196 ops/ms
Iteration   2: 13.120 ops/ms
Iteration   3: 13.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.173 ±(99.9%) 0.834 ops/ms [Average]
  (min, avg, max) = (13.120, 13.173, 13.202), stdev = 0.046
  CI (99.9%): [12.339, 14.007] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.175 ops/ms
# Warmup Iteration   2: 10.759 ops/ms
# Warmup Iteration   3: 10.779 ops/ms
Iteration   1: 10.967 ops/ms
Iteration   2: 10.901 ops/ms
Iteration   3: 10.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.947 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (10.901, 10.947, 10.973), stdev = 0.040
  CI (99.9%): [10.215, 11.679] (assumes normal distribution)


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.415 ±(99.9%) 0.003 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.438 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (2.415, 2.438, 2.464), stdev = 0.024
  CI (99.9%): [1.996, 2.880] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.558 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.382 ±(99.9%) 0.004 ms/op
Iteration   1: 2.383 ±(99.9%) 0.003 ms/op
Iteration   2: 2.397 ±(99.9%) 0.004 ms/op
Iteration   3: 2.399 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.393 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.383, 2.393, 2.399), stdev = 0.009
  CI (99.9%): [2.228, 2.558] (assumes normal distribution)


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.004 ms/op
Iteration   1: 2.408 ±(99.9%) 0.004 ms/op
Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
Iteration   3: 2.394 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.410 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.394, 2.410, 2.428), stdev = 0.017
  CI (99.9%): [2.096, 2.724] (assumes normal distribution)


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.004 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
Iteration   3: 2.946 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.961 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.946, 2.961, 2.980), stdev = 0.018
  CI (99.9%): [2.640, 3.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  6.718 ms/op
                 createUser·p0.9999: 13.533 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.495 ms/op
                 createUser·p0.9999: 12.557 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.756 ms/op
                 createUser·p0.9999: 11.914 ms/op
                 createUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386790
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 189853 
    [ 2.500,  3.750) = 192495 
    [ 3.750,  5.000) = 3453 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.448 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     13.683 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.585 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.387 ±(99.9%) 0.005 ms/op
Iteration   1: 2.369 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  4.743 ms/op
                 existUser·p0.9999: 12.952 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.590 ms/op
                 existUser·p0.999:  6.982 ms/op
                 existUser·p0.9999: 14.259 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   3: 2.389 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.741 ms/op
                 existUser·p0.999:  8.022 ms/op
                 existUser·p0.9999: 12.468 ms/op
                 existUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402100
  mean =      2.385 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 207295 
    [ 2.500,  3.750) = 191800 
    [ 3.750,  5.000) = 2182 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      6.813 ms/op
     p(99.9900) =     13.408 ms/op
     p(99.9990) =     14.581 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.684 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.006 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.551 ms/op
                 getUser·p0.999:  6.070 ms/op
                 getUser·p0.9999: 12.924 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  6.568 ms/op
                 getUser·p0.9999: 12.374 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  5.726 ms/op
                 getUser·p0.9999: 10.874 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391786
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 199484 
    [ 2.500,  3.750) = 187864 
    [ 3.750,  5.000) = 3581 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      6.129 ms/op
     p(99.9900) =     12.514 ms/op
     p(99.9990) =     13.192 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.394 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
Iteration   1: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.222 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 12.887 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.176 ms/op
                 listUser·p0.9999: 10.276 ms/op
                 listUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322092
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 100342 
    [ 2.500,  3.750) = 182823 
    [ 3.750,  5.000) = 31162 
    [ 5.000,  6.250) = 6211 
    [ 6.250,  7.500) = 743 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 317 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     11.569 ms/op
     p(99.9990) =     13.275 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.943 ± 0.268  ops/ms
ClientPb.existUser                       thrpt       3  13.373 ± 2.112  ops/ms
ClientPb.getUser                         thrpt       3  13.173 ± 0.834  ops/ms
ClientPb.listUser                        thrpt       3  10.947 ± 0.732  ops/ms
ClientPb.createUser                       avgt       3   2.438 ± 0.442   ms/op
ClientPb.existUser                        avgt       3   2.393 ± 0.165   ms/op
ClientPb.getUser                          avgt       3   2.410 ± 0.314   ms/op
ClientPb.listUser                         avgt       3   2.961 ± 0.321   ms/op
ClientPb.createUser                     sample  386790   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.448           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.714           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.189           ms/op
ClientPb.existUser                      sample  402100   2.385 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.892           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.813           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.408           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  391786   2.448 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.865           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.129           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.514           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.353           ms/op
ClientPb.listUser                       sample  322092   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.569           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
