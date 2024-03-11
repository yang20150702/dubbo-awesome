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
# Warmup Iteration   1: 5.110 ops/ms
# Warmup Iteration   2: 12.435 ops/ms
# Warmup Iteration   3: 12.809 ops/ms
Iteration   1: 12.886 ops/ms
Iteration   2: 13.139 ops/ms
Iteration   3: 13.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.018 ±(99.9%) 2.314 ops/ms [Average]
  (min, avg, max) = (12.886, 13.018, 13.139), stdev = 0.127
  CI (99.9%): [10.704, 15.332] (assumes normal distribution)


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
# Warmup Iteration   1: 8.218 ops/ms
# Warmup Iteration   2: 13.602 ops/ms
# Warmup Iteration   3: 13.740 ops/ms
Iteration   1: 13.745 ops/ms
Iteration   2: 13.540 ops/ms
Iteration   3: 13.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.619 ±(99.9%) 2.004 ops/ms [Average]
  (min, avg, max) = (13.540, 13.619, 13.745), stdev = 0.110
  CI (99.9%): [11.615, 15.624] (assumes normal distribution)


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
# Warmup Iteration   1: 7.914 ops/ms
# Warmup Iteration   2: 13.187 ops/ms
# Warmup Iteration   3: 13.257 ops/ms
Iteration   1: 13.477 ops/ms
Iteration   2: 13.298 ops/ms
Iteration   3: 13.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.410 ±(99.9%) 1.781 ops/ms [Average]
  (min, avg, max) = (13.298, 13.410, 13.477), stdev = 0.098
  CI (99.9%): [11.629, 15.190] (assumes normal distribution)


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
# Warmup Iteration   1: 7.009 ops/ms
# Warmup Iteration   2: 10.883 ops/ms
# Warmup Iteration   3: 11.036 ops/ms
Iteration   1: 10.986 ops/ms
Iteration   2: 11.021 ops/ms
Iteration   3: 11.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.064 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (10.986, 11.064, 11.185), stdev = 0.106
  CI (99.9%): [9.127, 13.000] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.387 ±(99.9%) 0.003 ms/op
Iteration   1: 2.411 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.418 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.411, 2.418, 2.424), stdev = 0.007
  CI (99.9%): [2.300, 2.537] (assumes normal distribution)


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
# Warmup Iteration   1: 3.551 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.398 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.362 ±(99.9%) 0.004 ms/op
Iteration   1: 2.404 ±(99.9%) 0.004 ms/op
Iteration   2: 2.396 ±(99.9%) 0.004 ms/op
Iteration   3: 2.404 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.401 ±(99.9%) 0.089 ms/op [Average]
  (min, avg, max) = (2.396, 2.401, 2.404), stdev = 0.005
  CI (99.9%): [2.312, 2.491] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.004 ms/op
Iteration   1: 2.385 ±(99.9%) 0.004 ms/op
Iteration   2: 2.399 ±(99.9%) 0.002 ms/op
Iteration   3: 2.412 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.399 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.385, 2.399, 2.412), stdev = 0.013
  CI (99.9%): [2.155, 2.642] (assumes normal distribution)


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.005 ms/op
Iteration   1: 2.948 ±(99.9%) 0.006 ms/op
Iteration   2: 2.937 ±(99.9%) 0.005 ms/op
Iteration   3: 2.942 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.942 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.937, 2.942, 2.948), stdev = 0.005
  CI (99.9%): [2.846, 3.038] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.006 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  6.263 ms/op
                 createUser·p0.9999: 13.648 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   2.941 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   3.602 ms/op
                 createUser·p0.999:  9.903 ms/op
                 createUser·p0.9999: 12.760 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.478 ms/op
                 createUser·p0.90:   2.949 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  7.342 ms/op
                 createUser·p0.9999: 10.158 ms/op
                 createUser·p1.00:   10.404 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 394229
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 197880 
    [ 2.500,  3.750) = 192268 
    [ 3.750,  5.000) = 3117 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     14.193 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.411 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.358 ±(99.9%) 0.005 ms/op
Iteration   1: 2.333 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.388 ms/op
                 existUser·p0.90:   2.834 ms/op
                 existUser·p0.95:   2.941 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  4.955 ms/op
                 existUser·p0.9999: 13.009 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   2: 2.391 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.989 ms/op
                 existUser·p0.999:  6.240 ms/op
                 existUser·p0.9999: 13.363 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.360 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.875 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  5.897 ms/op
                 existUser·p0.9999: 11.099 ms/op
                 existUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 406219
  mean =      2.361 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 216270 
    [ 2.500,  3.750) = 186748 
    [ 3.750,  5.000) = 2422 
    [ 5.000,  6.250) = 282 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.083 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.006 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  5.656 ms/op
                 getUser·p0.9999: 13.440 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  9.451 ms/op
                 getUser·p0.9999: 12.587 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  6.153 ms/op
                 getUser·p0.9999: 10.863 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388576
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 195100 
    [ 2.500,  3.750) = 188445 
    [ 3.750,  5.000) = 3850 
    [ 5.000,  6.250) = 634 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      7.692 ms/op
     p(99.9900) =     12.932 ms/op
     p(99.9990) =     14.094 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.009 ms/op
Iteration   1: 2.928 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.272 ms/op
                 listUser·p1.00:   13.124 ms/op

Iteration   2: 2.904 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.839 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   3: 2.904 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.612 ms/op
                 listUser·p0.9999: 18.611 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 329359
  mean =      2.912 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 110860 
    [ 2.500,  3.750) = 183725 
    [ 3.750,  5.000) = 28205 
    [ 5.000,  6.250) = 5201 
    [ 6.250,  7.500) = 466 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 238 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     13.397 ms/op
     p(99.9990) =     18.766 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.018 ± 2.314  ops/ms
ClientPb.existUser                       thrpt       3  13.619 ± 2.004  ops/ms
ClientPb.getUser                         thrpt       3  13.410 ± 1.781  ops/ms
ClientPb.listUser                        thrpt       3  11.064 ± 1.936  ops/ms
ClientPb.createUser                       avgt       3   2.418 ± 0.119   ms/op
ClientPb.existUser                        avgt       3   2.401 ± 0.089   ms/op
ClientPb.getUser                          avgt       3   2.399 ± 0.243   ms/op
ClientPb.listUser                         avgt       3   2.942 ± 0.096   ms/op
ClientPb.createUser                     sample  394229   2.433 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.735           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.494           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  406219   2.361 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.720           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.421           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.083           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.009           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.697           ms/op
ClientPb.getUser                        sample  388576   2.468 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.833           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.692           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.932           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.811           ms/op
ClientPb.listUser                       sample  329359   2.912 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.843           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.781           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.397           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.137           ms/op
