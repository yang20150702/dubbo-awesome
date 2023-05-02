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
# Warmup Iteration   1: 2.006 ops/ms
# Warmup Iteration   2: 4.644 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 9.255 ops/ms
Iteration   3: 8.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.898 ±(99.9%) 6.167 ops/ms [Average]
  (min, avg, max) = (8.583, 8.898, 9.255), stdev = 0.338
  CI (99.9%): [2.730, 15.065] (assumes normal distribution)


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
# Warmup Iteration   1: 3.118 ops/ms
# Warmup Iteration   2: 8.120 ops/ms
# Warmup Iteration   3: 9.387 ops/ms
Iteration   1: 10.068 ops/ms
Iteration   2: 9.506 ops/ms
Iteration   3: 9.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.839 ±(99.9%) 5.386 ops/ms [Average]
  (min, avg, max) = (9.506, 9.839, 10.068), stdev = 0.295
  CI (99.9%): [4.454, 15.225] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.705 ops/ms
# Warmup Iteration   2: 8.539 ops/ms
# Warmup Iteration   3: 8.734 ops/ms
Iteration   1: 9.136 ops/ms
Iteration   2: 8.855 ops/ms
Iteration   3: 9.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.192 ±(99.9%) 6.702 ops/ms [Average]
  (min, avg, max) = (8.855, 9.192, 9.584), stdev = 0.367
  CI (99.9%): [2.490, 15.894] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.559 ops/ms
# Warmup Iteration   2: 6.863 ops/ms
# Warmup Iteration   3: 7.686 ops/ms
Iteration   1: 8.358 ops/ms
Iteration   2: 8.178 ops/ms
Iteration   3: 8.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.245 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (8.178, 8.245, 8.358), stdev = 0.099
  CI (99.9%): [6.446, 10.044] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.780 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.005 ms/op
Iteration   1: 3.458 ±(99.9%) 0.003 ms/op
Iteration   2: 3.295 ±(99.9%) 0.005 ms/op
Iteration   3: 3.254 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.336 ±(99.9%) 1.965 ms/op [Average]
  (min, avg, max) = (3.254, 3.336, 3.458), stdev = 0.108
  CI (99.9%): [1.371, 5.301] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.377 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.004 ms/op
Iteration   1: 3.250 ±(99.9%) 0.006 ms/op
Iteration   2: 3.223 ±(99.9%) 0.011 ms/op
Iteration   3: 3.265 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.246 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.223, 3.246, 3.265), stdev = 0.021
  CI (99.9%): [2.863, 3.629] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.308 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.008 ms/op
Iteration   1: 3.383 ±(99.9%) 0.007 ms/op
Iteration   2: 3.289 ±(99.9%) 0.014 ms/op
Iteration   3: 3.401 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.358 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (3.289, 3.358, 3.401), stdev = 0.060
  CI (99.9%): [2.261, 4.455] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.799 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.009 ms/op
Iteration   1: 3.955 ±(99.9%) 0.007 ms/op
Iteration   2: 3.802 ±(99.9%) 0.013 ms/op
Iteration   3: 3.983 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.913 ±(99.9%) 1.771 ms/op [Average]
  (min, avg, max) = (3.802, 3.913, 3.983), stdev = 0.097
  CI (99.9%): [2.142, 5.684] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.440 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.009 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.395 ms/op
                 createUser·p0.999:  19.336 ms/op
                 createUser·p0.9999: 22.429 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.530 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  21.870 ms/op
                 createUser·p0.9999: 26.049 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.566 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  23.888 ms/op
                 createUser·p0.9999: 27.722 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275369
  mean =      3.485 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8517 
    [ 2.500,  5.000) = 259495 
    [ 5.000,  7.500) = 5991 
    [ 7.500, 10.000) = 871 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     20.927 ms/op
     p(99.9900) =     27.180 ms/op
     p(99.9990) =     28.007 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.033 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.008 ms/op
Iteration   1: 3.284 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 32.477 ms/op
                 existUser·p1.00:   34.275 ms/op

Iteration   2: 3.227 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  23.562 ms/op
                 existUser·p0.9999: 32.616 ms/op
                 existUser·p1.00:   41.353 ms/op

Iteration   3: 3.267 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  14.532 ms/op
                 existUser·p0.9999: 33.522 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294455
  mean =      3.259 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 289508 
    [ 5.000, 10.000) = 4461 
    [10.000, 15.000) = 166 
    [15.000, 20.000) = 30 
    [20.000, 25.000) = 176 
    [25.000, 30.000) = 18 
    [30.000, 35.000) = 95 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     32.819 ms/op
     p(99.9990) =     34.213 ms/op
     p(99.9999) =     41.353 ms/op
    p(100.0000) =     41.353 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.634 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.010 ms/op
Iteration   1: 3.444 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.366 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  19.857 ms/op
                 getUser·p0.9999: 28.106 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.641 ms/op
                 getUser·p0.999:  17.523 ms/op
                 getUser·p0.9999: 27.558 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  18.390 ms/op
                 getUser·p0.9999: 26.058 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283881
  mean =      3.379 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7099 
    [ 2.500,  5.000) = 269767 
    [ 5.000,  7.500) = 5789 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.055 ms/op
     p(99.9000) =     18.452 ms/op
     p(99.9900) =     27.545 ms/op
     p(99.9990) =     29.179 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 10.507 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.013 ms/op
Iteration   1: 3.925 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  20.369 ms/op
                 listUser·p0.9999: 24.801 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 3.833 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.943 ms/op
                 listUser·p0.9999: 17.743 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 3.938 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  14.331 ms/op
                 listUser·p0.9999: 23.388 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246206
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 239755 
    [ 5.000,  7.500) = 4617 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.152 ms/op
     p(99.9900) =     23.933 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.898 ± 6.167  ops/ms
ClientPb.existUser                       thrpt       3   9.839 ± 5.386  ops/ms
ClientPb.getUser                         thrpt       3   9.192 ± 6.702  ops/ms
ClientPb.listUser                        thrpt       3   8.245 ± 1.799  ops/ms
ClientPb.createUser                       avgt       3   3.336 ± 1.965   ms/op
ClientPb.existUser                        avgt       3   3.246 ± 0.383   ms/op
ClientPb.getUser                          avgt       3   3.358 ± 1.097   ms/op
ClientPb.listUser                         avgt       3   3.913 ± 1.771   ms/op
ClientPb.createUser                     sample  275369   3.485 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.566           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.927           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.180           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  294455   3.259 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.300           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.819           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.353           ms/op
ClientPb.getUser                        sample  283881   3.379 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.366           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.055           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.452           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.545           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.491           ms/op
ClientPb.listUser                       sample  246206   3.898 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.781           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.152           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.933           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.444           ms/op
