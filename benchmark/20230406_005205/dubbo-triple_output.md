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
# Warmup Iteration   1: 1.504 ops/ms
# Warmup Iteration   2: 3.418 ops/ms
# Warmup Iteration   3: 7.513 ops/ms
Iteration   1: 7.416 ops/ms
Iteration   2: 7.797 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.864 ±(99.9%) 8.854 ops/ms [Average]
  (min, avg, max) = (7.416, 7.864, 8.380), stdev = 0.485
  CI (99.9%): [≈ 0, 16.718] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.566 ops/ms
# Warmup Iteration   2: 6.906 ops/ms
# Warmup Iteration   3: 8.057 ops/ms
Iteration   1: 8.622 ops/ms
Iteration   2: 8.877 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.588 ±(99.9%) 5.623 ops/ms [Average]
  (min, avg, max) = (8.264, 8.588, 8.877), stdev = 0.308
  CI (99.9%): [2.964, 14.211] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.199 ops/ms
# Warmup Iteration   2: 5.992 ops/ms
# Warmup Iteration   3: 7.564 ops/ms
Iteration   1: 6.965 ops/ms
Iteration   2: 7.475 ops/ms
Iteration   3: 8.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.501 ±(99.9%) 10.038 ops/ms [Average]
  (min, avg, max) = (6.965, 7.501, 8.064), stdev = 0.550
  CI (99.9%): [≈ 0, 17.539] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.867 ops/ms
# Warmup Iteration   2: 4.524 ops/ms
# Warmup Iteration   3: 5.564 ops/ms
Iteration   1: 5.953 ops/ms
Iteration   2: 6.015 ops/ms
Iteration   3: 6.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.993 ±(99.9%) 0.646 ops/ms [Average]
  (min, avg, max) = (5.953, 5.993, 6.015), stdev = 0.035
  CI (99.9%): [5.347, 6.639] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.587 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.357 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.002 ms/op
Iteration   1: 3.345 ±(99.9%) 0.004 ms/op
Iteration   2: 3.276 ±(99.9%) 0.003 ms/op
Iteration   3: 3.263 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.295 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (3.263, 3.295, 3.345), stdev = 0.044
  CI (99.9%): [2.488, 4.101] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.930 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.003 ms/op
Iteration   1: 3.219 ±(99.9%) 0.006 ms/op
Iteration   2: 3.439 ±(99.9%) 0.003 ms/op
Iteration   3: 3.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.260 ±(99.9%) 2.965 ms/op [Average]
  (min, avg, max) = (3.121, 3.260, 3.439), stdev = 0.163
  CI (99.9%): [0.295, 6.225] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.866 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.004 ms/op
Iteration   1: 3.303 ±(99.9%) 0.001 ms/op
Iteration   2: 3.305 ±(99.9%) 0.005 ms/op
Iteration   3: 3.244 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.284 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (3.244, 3.284, 3.305), stdev = 0.034
  CI (99.9%): [2.656, 3.912] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.200 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.006 ms/op
Iteration   1: 3.924 ±(99.9%) 0.012 ms/op
Iteration   2: 3.909 ±(99.9%) 0.010 ms/op
Iteration   3: 3.909 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.914 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (3.909, 3.914, 3.924), stdev = 0.009
  CI (99.9%): [3.752, 4.076] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.605 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.009 ms/op
Iteration   1: 3.213 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  13.885 ms/op
                 createUser·p0.9999: 21.694 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  19.830 ms/op
                 createUser·p0.9999: 26.247 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   3: 3.254 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.394 ms/op
                 createUser·p0.999:  14.495 ms/op
                 createUser·p0.9999: 21.370 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298634
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16078 
    [ 2.500,  5.000) = 277767 
    [ 5.000,  7.500) = 3841 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     16.861 ms/op
     p(99.9900) =     25.057 ms/op
     p(99.9990) =     27.139 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.299 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
Iteration   1: 3.205 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.881 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 20.186 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.351 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 21.609 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   3: 3.263 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  13.138 ms/op
                 existUser·p0.9999: 25.107 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293321
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10768 
    [ 2.500,  5.000) = 275044 
    [ 5.000,  7.500) = 6770 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.825 ms/op
     p(99.9900) =     23.538 ms/op
     p(99.9990) =     25.415 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.788 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.010 ms/op
Iteration   1: 3.295 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.511 ms/op
                 getUser·p0.999:  12.511 ms/op
                 getUser·p0.9999: 21.580 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   2: 3.397 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  19.422 ms/op
                 getUser·p0.9999: 25.120 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.659 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  17.026 ms/op
                 getUser·p0.9999: 22.505 ms/op
                 getUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278635
  mean =      3.444 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3558 
    [ 2.500,  5.000) = 268387 
    [ 5.000,  7.500) = 5570 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     23.597 ms/op
     p(99.9990) =     25.402 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.607 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.013 ms/op
Iteration   1: 4.078 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  18.268 ms/op
                 listUser·p0.9999: 20.976 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 4.034 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 3.958 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  14.933 ms/op
                 listUser·p0.9999: 27.260 ms/op
                 listUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238586
  mean =      4.023 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 229242 
    [ 5.000,  7.500) = 6882 
    [ 7.500, 10.000) = 1613 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     15.883 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     27.776 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.864 ±  8.854  ops/ms
ClientPb.existUser                       thrpt       3   8.588 ±  5.623  ops/ms
ClientPb.getUser                         thrpt       3   7.501 ± 10.038  ops/ms
ClientPb.listUser                        thrpt       3   5.993 ±  0.646  ops/ms
ClientPb.createUser                       avgt       3   3.295 ±  0.806   ms/op
ClientPb.existUser                        avgt       3   3.260 ±  2.965   ms/op
ClientPb.getUser                          avgt       3   3.284 ±  0.628   ms/op
ClientPb.listUser                         avgt       3   3.914 ±  0.162   ms/op
ClientPb.createUser                     sample  298634   3.212 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.972            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.490            ms/op
ClientPb.createUser:createUser·p0.95    sample           3.740            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603            ms/op
ClientPb.createUser:createUser·p0.999   sample          16.861            ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.057            ms/op
ClientPb.createUser:createUser·p1.00    sample          27.656            ms/op
ClientPb.existUser                      sample  293321   3.272 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.383            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808            ms/op
ClientPb.existUser:existUser·p0.999     sample          11.825            ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.538            ms/op
ClientPb.existUser:existUser·p1.00      sample          26.509            ms/op
ClientPb.getUser                        sample  278635   3.444 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.259            ms/op
ClientPb.getUser:getUser·p0.999         sample          17.039            ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.597            ms/op
ClientPb.getUser:getUser·p1.00          sample          25.559            ms/op
ClientPb.listUser                       sample  238586   4.023 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.391            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.545            ms/op
ClientPb.listUser:listUser·p0.999       sample          15.883            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.034            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.017            ms/op
