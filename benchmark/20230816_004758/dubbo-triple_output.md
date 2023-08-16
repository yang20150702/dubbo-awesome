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
# Warmup Iteration   1: 2.249 ops/ms
# Warmup Iteration   2: 5.739 ops/ms
# Warmup Iteration   3: 8.049 ops/ms
Iteration   1: 9.023 ops/ms
Iteration   2: 9.059 ops/ms
Iteration   3: 9.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.063 ±(99.9%) 0.778 ops/ms [Average]
  (min, avg, max) = (9.023, 9.063, 9.108), stdev = 0.043
  CI (99.9%): [8.286, 9.841] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 8.689 ops/ms
# Warmup Iteration   3: 9.483 ops/ms
Iteration   1: 9.661 ops/ms
Iteration   2: 9.522 ops/ms
Iteration   3: 9.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.458 ±(99.9%) 4.387 ops/ms [Average]
  (min, avg, max) = (9.193, 9.458, 9.661), stdev = 0.240
  CI (99.9%): [5.071, 13.846] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.757 ops/ms
# Warmup Iteration   2: 8.545 ops/ms
# Warmup Iteration   3: 8.779 ops/ms
Iteration   1: 8.732 ops/ms
Iteration   2: 9.323 ops/ms
Iteration   3: 9.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.072 ±(99.9%) 5.575 ops/ms [Average]
  (min, avg, max) = (8.732, 9.072, 9.323), stdev = 0.306
  CI (99.9%): [3.498, 14.647] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.846 ops/ms
# Warmup Iteration   2: 6.980 ops/ms
# Warmup Iteration   3: 7.521 ops/ms
Iteration   1: 7.734 ops/ms
Iteration   2: 8.030 ops/ms
Iteration   3: 7.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.799 ±(99.9%) 3.775 ops/ms [Average]
  (min, avg, max) = (7.632, 7.799, 8.030), stdev = 0.207
  CI (99.9%): [4.024, 11.574] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.453 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.008 ms/op
Iteration   1: 3.465 ±(99.9%) 0.007 ms/op
Iteration   2: 3.521 ±(99.9%) 0.009 ms/op
Iteration   3: 3.477 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.487 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (3.465, 3.487, 3.521), stdev = 0.029
  CI (99.9%): [2.950, 4.025] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.226 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.003 ms/op
Iteration   1: 3.426 ±(99.9%) 0.010 ms/op
Iteration   2: 3.363 ±(99.9%) 0.005 ms/op
Iteration   3: 3.415 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.401 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (3.363, 3.401, 3.426), stdev = 0.034
  CI (99.9%): [2.790, 4.013] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.097 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.004 ms/op
Iteration   1: 3.431 ±(99.9%) 0.008 ms/op
Iteration   2: 3.510 ±(99.9%) 0.005 ms/op
Iteration   3: 3.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.486 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (3.431, 3.486, 3.517), stdev = 0.048
  CI (99.9%): [2.615, 4.358] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.464 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.011 ms/op
Iteration   1: 4.181 ±(99.9%) 0.011 ms/op
Iteration   2: 4.018 ±(99.9%) 0.014 ms/op
Iteration   3: 4.156 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.118 ±(99.9%) 1.598 ms/op [Average]
  (min, avg, max) = (4.018, 4.118, 4.181), stdev = 0.088
  CI (99.9%): [2.520, 5.716] (assumes normal distribution)


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
# Warmup Iteration   1: 9.523 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.011 ms/op
Iteration   1: 3.508 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  21.070 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.510 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.710 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  23.132 ms/op
                 createUser·p0.9999: 25.589 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   3: 3.531 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  22.279 ms/op
                 createUser·p0.9999: 28.242 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272846
  mean =      3.516 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13495 
    [ 2.500,  5.000) = 249897 
    [ 5.000,  7.500) = 7979 
    [ 7.500, 10.000) = 944 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.296 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     26.566 ms/op
     p(99.9990) =     28.681 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.537 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.010 ms/op
Iteration   1: 3.436 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  20.568 ms/op
                 existUser·p0.9999: 23.859 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 3.346 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  22.318 ms/op
                 existUser·p0.9999: 25.606 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   3: 3.577 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  13.365 ms/op
                 existUser·p0.9999: 28.642 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278005
  mean =      3.450 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11470 
    [ 2.500,  5.000) = 258365 
    [ 5.000,  7.500) = 6495 
    [ 7.500, 10.000) = 1090 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 9.971 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.013 ms/op
Iteration   1: 3.554 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  21.201 ms/op
                 getUser·p0.9999: 23.200 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 3.668 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.883 ms/op
                 getUser·p0.999:  23.579 ms/op
                 getUser·p0.9999: 27.211 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.613 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.870 ms/op
                 getUser·p0.999:  20.379 ms/op
                 getUser·p0.9999: 28.612 ms/op
                 getUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265653
  mean =      3.611 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3125 
    [ 2.500,  5.000) = 252535 
    [ 5.000,  7.500) = 8074 
    [ 7.500, 10.000) = 1336 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     21.158 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     29.528 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 10.724 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.015 ms/op
Iteration   1: 4.060 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  21.447 ms/op
                 listUser·p0.9999: 26.972 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   2: 4.056 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 18.130 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  15.877 ms/op
                 listUser·p0.9999: 24.633 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237074
  mean =      4.047 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 227678 
    [ 5.000,  7.500) = 6193 
    [ 7.500, 10.000) = 1983 
    [10.000, 12.500) = 608 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     17.360 ms/op
     p(99.9900) =     25.864 ms/op
     p(99.9990) =     27.239 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.063 ± 0.778  ops/ms
ClientPb.existUser                       thrpt       3   9.458 ± 4.387  ops/ms
ClientPb.getUser                         thrpt       3   9.072 ± 5.575  ops/ms
ClientPb.listUser                        thrpt       3   7.799 ± 3.775  ops/ms
ClientPb.createUser                       avgt       3   3.487 ± 0.538   ms/op
ClientPb.existUser                        avgt       3   3.401 ± 0.611   ms/op
ClientPb.getUser                          avgt       3   3.486 ± 0.872   ms/op
ClientPb.listUser                         avgt       3   4.118 ± 1.598   ms/op
ClientPb.createUser                     sample  272846   3.516 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.764           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.296           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.266           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.566           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  278005   3.450 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.503           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.746           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.623           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  265653   3.611 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.457           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.158           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.591           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.819           ms/op
ClientPb.listUser                       sample  237074   4.047 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.876           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.360           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.864           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.558           ms/op
