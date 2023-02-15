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
# Warmup Iteration   1: 1.569 ops/ms
# Warmup Iteration   2: 3.551 ops/ms
# Warmup Iteration   3: 7.451 ops/ms
Iteration   1: 7.001 ops/ms
Iteration   2: 7.975 ops/ms
Iteration   3: 8.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.672 ±(99.9%) 10.619 ops/ms [Average]
  (min, avg, max) = (7.001, 7.672, 8.039), stdev = 0.582
  CI (99.9%): [≈ 0, 18.291] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.233 ops/ms
# Warmup Iteration   2: 6.209 ops/ms
# Warmup Iteration   3: 7.895 ops/ms
Iteration   1: 8.369 ops/ms
Iteration   2: 8.671 ops/ms
Iteration   3: 8.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.441 ±(99.9%) 3.733 ops/ms [Average]
  (min, avg, max) = (8.282, 8.441, 8.671), stdev = 0.205
  CI (99.9%): [4.707, 12.174] (assumes normal distribution)


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
# Warmup Iteration   1: 2.152 ops/ms
# Warmup Iteration   2: 5.857 ops/ms
# Warmup Iteration   3: 7.644 ops/ms
Iteration   1: 7.548 ops/ms
Iteration   2: 7.592 ops/ms
Iteration   3: 8.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.865 ±(99.9%) 9.331 ops/ms [Average]
  (min, avg, max) = (7.548, 7.865, 8.455), stdev = 0.511
  CI (99.9%): [≈ 0, 17.196] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.163 ops/ms
# Warmup Iteration   2: 5.462 ops/ms
# Warmup Iteration   3: 6.753 ops/ms
Iteration   1: 6.763 ops/ms
Iteration   2: 7.155 ops/ms
Iteration   3: 7.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.024 ±(99.9%) 4.126 ops/ms [Average]
  (min, avg, max) = (6.763, 7.024, 7.155), stdev = 0.226
  CI (99.9%): [2.897, 11.150] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.316 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.906 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.406 ±(99.9%) 0.003 ms/op
Iteration   1: 3.970 ±(99.9%) 0.005 ms/op
Iteration   2: 3.871 ±(99.9%) 0.013 ms/op
Iteration   3: 4.040 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.960 ±(99.9%) 1.553 ms/op [Average]
  (min, avg, max) = (3.871, 3.960, 4.040), stdev = 0.085
  CI (99.9%): [2.408, 5.513] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.027 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.003 ms/op
Iteration   1: 4.061 ±(99.9%) 0.007 ms/op
Iteration   2: 3.889 ±(99.9%) 0.006 ms/op
Iteration   3: 3.732 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.894 ±(99.9%) 3.000 ms/op [Average]
  (min, avg, max) = (3.732, 3.894, 4.061), stdev = 0.164
  CI (99.9%): [0.894, 6.894] (assumes normal distribution)


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
# Warmup Iteration   1: 11.897 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.005 ms/op
Iteration   1: 4.060 ±(99.9%) 0.007 ms/op
Iteration   2: 3.849 ±(99.9%) 0.016 ms/op
Iteration   3: 4.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.997 ±(99.9%) 2.359 ms/op [Average]
  (min, avg, max) = (3.849, 3.997, 4.084), stdev = 0.129
  CI (99.9%): [1.638, 6.356] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 11.932 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 6.267 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.919 ±(99.9%) 0.005 ms/op
Iteration   1: 4.697 ±(99.9%) 0.008 ms/op
Iteration   2: 4.655 ±(99.9%) 0.015 ms/op
Iteration   3: 4.595 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.649 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (4.595, 4.649, 4.697), stdev = 0.051
  CI (99.9%): [3.710, 5.588] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.815 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.109 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.675 ±(99.9%) 0.023 ms/op
Iteration   1: 4.188 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   6.365 ms/op
                 createUser·p0.99:   8.377 ms/op
                 createUser·p0.999:  23.743 ms/op
                 createUser·p0.9999: 27.176 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 4.068 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   8.599 ms/op
                 createUser·p0.999:  19.114 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   3: 3.866 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   7.352 ms/op
                 createUser·p0.999:  28.680 ms/op
                 createUser·p0.9999: 31.767 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237797
  mean =      4.036 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 500 
    [ 2.500,  5.000) = 217008 
    [ 5.000,  7.500) = 16448 
    [ 7.500, 10.000) = 2806 
    [10.000, 12.500) = 521 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     23.698 ms/op
     p(99.9900) =     31.301 ms/op
     p(99.9990) =     31.977 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 12.731 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.014 ms/op
Iteration   1: 3.832 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.835 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  10.941 ms/op
                 existUser·p0.9999: 24.630 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   2: 3.856 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   8.315 ms/op
                 existUser·p0.999:  23.460 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.617 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 29.108 ms/op
                 existUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254977
  mean =      3.765 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 511 
    [ 2.500,  5.000) = 244563 
    [ 5.000,  7.500) = 7816 
    [ 7.500, 10.000) = 1423 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     16.125 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     30.405 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.989 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.916 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.015 ms/op
Iteration   1: 4.119 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  21.398 ms/op
                 getUser·p0.9999: 24.591 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 4.045 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.860 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  13.186 ms/op
                 getUser·p0.9999: 26.872 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  27.344 ms/op
                 getUser·p0.9999: 35.238 ms/op
                 getUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240105
  mean =      3.999 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 263 
    [ 2.500,  5.000) = 225239 
    [ 5.000,  7.500) = 11064 
    [ 7.500, 10.000) = 2788 
    [10.000, 12.500) = 398 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     21.332 ms/op
     p(99.9900) =     33.357 ms/op
     p(99.9990) =     35.822 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 14.245 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.740 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.832 ±(99.9%) 0.017 ms/op
Iteration   1: 4.937 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.823 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   7.528 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  24.586 ms/op
                 listUser·p0.9999: 27.003 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 4.810 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  22.231 ms/op
                 listUser·p0.9999: 26.248 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   3: 4.735 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 19.505 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198897
  mean =      4.826 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 155385 
    [ 5.000,  7.500) = 36152 
    [ 7.500, 10.000) = 5498 
    [10.000, 12.500) = 1095 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     26.644 ms/op
     p(99.9990) =     27.926 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.672 ± 10.619  ops/ms
ClientPb.existUser                       thrpt       3   8.441 ±  3.733  ops/ms
ClientPb.getUser                         thrpt       3   7.865 ±  9.331  ops/ms
ClientPb.listUser                        thrpt       3   7.024 ±  4.126  ops/ms
ClientPb.createUser                       avgt       3   3.960 ±  1.553   ms/op
ClientPb.existUser                        avgt       3   3.894 ±  3.000   ms/op
ClientPb.getUser                          avgt       3   3.997 ±  2.359   ms/op
ClientPb.listUser                         avgt       3   4.649 ±  0.939   ms/op
ClientPb.createUser                     sample  237797   4.036 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.587            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.833            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.743            ms/op
ClientPb.createUser:createUser·p0.99    sample           8.241            ms/op
ClientPb.createUser:createUser·p0.999   sample          23.698            ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.301            ms/op
ClientPb.createUser:createUser·p1.00    sample          32.080            ms/op
ClientPb.existUser                      sample  254977   3.765 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.765            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.609            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.166            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.694            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.209            ms/op
ClientPb.existUser:existUser·p0.999     sample          16.125            ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.312            ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474            ms/op
ClientPb.getUser                        sample  240105   3.999 ±  0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.032            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.805            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.276            ms/op
ClientPb.getUser:getUser·p0.99          sample           8.118            ms/op
ClientPb.getUser:getUser·p0.999         sample          21.332            ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.357            ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176            ms/op
ClientPb.listUser                       sample  198897   4.826 ±  0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.278            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.644            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.939            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.814            ms/op
ClientPb.listUser:listUser·p0.999       sample          21.692            ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.644            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606            ms/op
