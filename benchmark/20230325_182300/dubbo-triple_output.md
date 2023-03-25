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
# Warmup Iteration   1: 2.300 ops/ms
# Warmup Iteration   2: 6.218 ops/ms
# Warmup Iteration   3: 8.865 ops/ms
Iteration   1: 9.354 ops/ms
Iteration   2: 9.317 ops/ms
Iteration   3: 9.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.437 ±(99.9%) 3.214 ops/ms [Average]
  (min, avg, max) = (9.317, 9.437, 9.639), stdev = 0.176
  CI (99.9%): [6.223, 12.651] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.953 ops/ms
# Warmup Iteration   2: 8.555 ops/ms
# Warmup Iteration   3: 9.579 ops/ms
Iteration   1: 9.702 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 9.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.843 ±(99.9%) 3.685 ops/ms [Average]
  (min, avg, max) = (9.702, 9.843, 10.075), stdev = 0.202
  CI (99.9%): [6.158, 13.528] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.903 ops/ms
# Warmup Iteration   2: 8.431 ops/ms
# Warmup Iteration   3: 8.835 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.680 ops/ms
Iteration   3: 9.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.416 ±(99.9%) 4.745 ops/ms [Average]
  (min, avg, max) = (9.160, 9.416, 9.680), stdev = 0.260
  CI (99.9%): [4.671, 14.162] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.897 ops/ms
# Warmup Iteration   2: 7.212 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 8.142 ops/ms
Iteration   2: 8.230 ops/ms
Iteration   3: 8.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.215 ±(99.9%) 1.208 ops/ms [Average]
  (min, avg, max) = (8.142, 8.215, 8.272), stdev = 0.066
  CI (99.9%): [7.007, 9.422] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.779 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.005 ms/op
Iteration   1: 3.510 ±(99.9%) 0.006 ms/op
Iteration   2: 3.366 ±(99.9%) 0.009 ms/op
Iteration   3: 3.322 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.399 ±(99.9%) 1.791 ms/op [Average]
  (min, avg, max) = (3.322, 3.399, 3.510), stdev = 0.098
  CI (99.9%): [1.609, 5.190] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.051 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.004 ms/op
Iteration   1: 3.388 ±(99.9%) 0.007 ms/op
Iteration   2: 3.368 ±(99.9%) 0.006 ms/op
Iteration   3: 3.327 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.361 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.327, 3.361, 3.388), stdev = 0.031
  CI (99.9%): [2.794, 3.927] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.231 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.006 ms/op
Iteration   1: 3.290 ±(99.9%) 0.005 ms/op
Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
Iteration   3: 3.373 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.318 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (3.289, 3.318, 3.373), stdev = 0.048
  CI (99.9%): [2.436, 4.200] (assumes normal distribution)


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
# Warmup Iteration   1: 10.685 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.009 ms/op
Iteration   1: 3.857 ±(99.9%) 0.009 ms/op
Iteration   2: 3.993 ±(99.9%) 0.007 ms/op
Iteration   3: 3.899 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.917 ±(99.9%) 1.269 ms/op [Average]
  (min, avg, max) = (3.857, 3.917, 3.993), stdev = 0.070
  CI (99.9%): [2.647, 5.186] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.779 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.860 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
Iteration   1: 3.389 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  19.104 ms/op
                 createUser·p0.9999: 25.008 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   2: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 22.175 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.829 ms/op
                 createUser·p0.999:  18.893 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282377
  mean =      3.403 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10550 
    [ 2.500,  5.000) = 264788 
    [ 5.000,  7.500) = 5820 
    [ 7.500, 10.000) = 733 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     19.059 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 8.282 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.008 ms/op
Iteration   1: 3.377 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  20.100 ms/op
                 existUser·p0.9999: 26.767 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   2: 3.284 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  10.760 ms/op
                 existUser·p0.9999: 36.472 ms/op
                 existUser·p1.00:   37.421 ms/op

Iteration   3: 3.267 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.376 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.219 ms/op
                 existUser·p0.999:  12.106 ms/op
                 existUser·p0.9999: 27.827 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289801
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14072 
    [ 2.500,  5.000) = 271221 
    [ 5.000,  7.500) = 3678 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     12.302 ms/op
     p(99.9900) =     32.507 ms/op
     p(99.9990) =     37.107 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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
# Warmup Iteration   1: 10.582 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.009 ms/op
Iteration   1: 3.414 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  20.168 ms/op
                 getUser·p0.9999: 23.188 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.330 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  23.472 ms/op
                 getUser·p0.9999: 33.646 ms/op
                 getUser·p1.00:   35.979 ms/op

Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  16.413 ms/op
                 getUser·p0.9999: 23.900 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285777
  mean =      3.356 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3019 
    [ 2.500,  5.000) = 275512 
    [ 5.000,  7.500) = 6213 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     34.977 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 8.925 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.012 ms/op
Iteration   1: 4.042 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  20.607 ms/op
                 listUser·p0.9999: 26.026 ms/op
                 listUser·p1.00:   26.968 ms/op

Iteration   2: 4.049 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 3.934 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 16.806 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239458
  mean =      4.007 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 230933 
    [ 5.000,  7.500) = 6201 
    [ 7.500, 10.000) = 1597 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     26.524 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.437 ± 3.214  ops/ms
ClientPb.existUser                       thrpt       3   9.843 ± 3.685  ops/ms
ClientPb.getUser                         thrpt       3   9.416 ± 4.745  ops/ms
ClientPb.listUser                        thrpt       3   8.215 ± 1.208  ops/ms
ClientPb.createUser                       avgt       3   3.399 ± 1.791   ms/op
ClientPb.existUser                        avgt       3   3.361 ± 0.566   ms/op
ClientPb.getUser                          avgt       3   3.318 ± 0.882   ms/op
ClientPb.listUser                         avgt       3   3.917 ± 1.269   ms/op
ClientPb.createUser                     sample  282377   3.403 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.348           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.177           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.059           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.936           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.771           ms/op
ClientPb.existUser                      sample  289801   3.309 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.376           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.507           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.421           ms/op
ClientPb.getUser                        sample  285777   3.356 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.135           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.121           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.818           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.979           ms/op
ClientPb.listUser                       sample  239458   4.007 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.331           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.151           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.968           ms/op
