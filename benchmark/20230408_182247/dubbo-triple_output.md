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
# Warmup Iteration   1: 2.101 ops/ms
# Warmup Iteration   2: 5.996 ops/ms
# Warmup Iteration   3: 8.882 ops/ms
Iteration   1: 9.203 ops/ms
Iteration   2: 9.694 ops/ms
Iteration   3: 9.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.517 ±(99.9%) 4.971 ops/ms [Average]
  (min, avg, max) = (9.203, 9.517, 9.694), stdev = 0.272
  CI (99.9%): [4.546, 14.489] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.468 ops/ms
# Warmup Iteration   2: 9.417 ops/ms
# Warmup Iteration   3: 9.559 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 9.950 ops/ms
Iteration   3: 9.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.875 ±(99.9%) 2.463 ops/ms [Average]
  (min, avg, max) = (9.719, 9.875, 9.956), stdev = 0.135
  CI (99.9%): [7.412, 12.338] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.140 ops/ms
# Warmup Iteration   2: 8.584 ops/ms
# Warmup Iteration   3: 8.766 ops/ms
Iteration   1: 9.505 ops/ms
Iteration   2: 9.597 ops/ms
Iteration   3: 9.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.539 ±(99.9%) 0.929 ops/ms [Average]
  (min, avg, max) = (9.505, 9.539, 9.597), stdev = 0.051
  CI (99.9%): [8.610, 10.468] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.868 ops/ms
# Warmup Iteration   2: 7.445 ops/ms
# Warmup Iteration   3: 7.583 ops/ms
Iteration   1: 7.855 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 8.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.072 ±(99.9%) 3.981 ops/ms [Average]
  (min, avg, max) = (7.855, 8.072, 8.291), stdev = 0.218
  CI (99.9%): [4.091, 12.053] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.420 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.006 ms/op
Iteration   1: 3.400 ±(99.9%) 0.007 ms/op
Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
Iteration   3: 3.436 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.386 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (3.324, 3.386, 3.436), stdev = 0.057
  CI (99.9%): [2.346, 4.427] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.661 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.004 ms/op
Iteration   1: 3.285 ±(99.9%) 0.007 ms/op
Iteration   2: 3.218 ±(99.9%) 0.010 ms/op
Iteration   3: 3.369 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.290 ±(99.9%) 1.383 ms/op [Average]
  (min, avg, max) = (3.218, 3.290, 3.369), stdev = 0.076
  CI (99.9%): [1.907, 4.674] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.060 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.005 ms/op
Iteration   1: 3.398 ±(99.9%) 0.010 ms/op
Iteration   2: 3.470 ±(99.9%) 0.007 ms/op
Iteration   3: 3.447 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.438 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (3.398, 3.438, 3.470), stdev = 0.037
  CI (99.9%): [2.766, 4.111] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.798 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.888 ±(99.9%) 0.016 ms/op
Iteration   2: 4.117 ±(99.9%) 0.010 ms/op
Iteration   3: 3.896 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.967 ±(99.9%) 2.367 ms/op [Average]
  (min, avg, max) = (3.888, 3.967, 4.117), stdev = 0.130
  CI (99.9%): [1.600, 6.334] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.842 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
Iteration   1: 3.399 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  19.197 ms/op
                 createUser·p0.9999: 23.493 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.364 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  20.226 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  19.815 ms/op
                 createUser·p0.9999: 26.123 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280573
  mean =      3.420 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11474 
    [ 2.500,  5.000) = 262300 
    [ 5.000,  7.500) = 5656 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     24.148 ms/op
     p(99.9990) =     27.499 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.420 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
Iteration   1: 3.344 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  12.420 ms/op
                 existUser·p0.9999: 25.358 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 29.262 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  21.201 ms/op
                 existUser·p0.9999: 27.453 ms/op
                 existUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287565
  mean =      3.338 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14446 
    [ 2.500,  5.000) = 267753 
    [ 5.000,  7.500) = 4518 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     28.098 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 9.637 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
Iteration   1: 3.606 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  22.468 ms/op
                 getUser·p0.9999: 32.080 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   2: 3.383 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  24.134 ms/op
                 getUser·p0.9999: 29.771 ms/op
                 getUser·p1.00:   32.244 ms/op

Iteration   3: 3.393 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  21.346 ms/op
                 getUser·p0.9999: 40.260 ms/op
                 getUser·p1.00:   41.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277358
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 268766 
    [ 5.000, 10.000) = 8189 
    [10.000, 15.000) = 110 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 90 
    [25.000, 30.000) = 117 
    [30.000, 35.000) = 49 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     21.828 ms/op
     p(99.9900) =     39.273 ms/op
     p(99.9990) =     41.353 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


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
# Warmup Iteration   1: 11.939 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.591 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.013 ms/op
Iteration   1: 4.082 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.678 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 29.300 ms/op
                 listUser·p1.00:   29.950 ms/op

Iteration   2: 3.935 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.003 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.936 ms/op
                 listUser·p0.999:  15.533 ms/op
                 listUser·p0.9999: 18.580 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239397
  mean =      4.006 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 230324 
    [ 5.000,  7.500) = 6721 
    [ 7.500, 10.000) = 1501 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     27.726 ms/op
     p(99.9990) =     29.630 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.517 ± 4.971  ops/ms
ClientPb.existUser                       thrpt       3   9.875 ± 2.463  ops/ms
ClientPb.getUser                         thrpt       3   9.539 ± 0.929  ops/ms
ClientPb.listUser                        thrpt       3   8.072 ± 3.981  ops/ms
ClientPb.createUser                       avgt       3   3.386 ± 1.041   ms/op
ClientPb.existUser                        avgt       3   3.290 ± 1.383   ms/op
ClientPb.getUser                          avgt       3   3.438 ± 0.673   ms/op
ClientPb.listUser                         avgt       3   3.967 ± 2.367   ms/op
ClientPb.createUser                     sample  280573   3.420 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.602           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.148           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.623           ms/op
ClientPb.existUser                      sample  287565   3.338 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.098           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474           ms/op
ClientPb.getUser                        sample  277358   3.458 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.828           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.273           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.419           ms/op
ClientPb.listUser                       sample  239397   4.006 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.678           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.726           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.950           ms/op
