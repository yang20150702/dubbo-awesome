# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.510 ops/ms
# Warmup Iteration   2: 3.144 ops/ms
# Warmup Iteration   3: 6.519 ops/ms
Iteration   1: 7.432 ops/ms
Iteration   2: 7.834 ops/ms
Iteration   3: 7.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.703 ±(99.9%) 4.279 ops/ms [Average]
  (min, avg, max) = (7.432, 7.703, 7.843), stdev = 0.235
  CI (99.9%): [3.423, 11.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 2.209 ops/ms
# Warmup Iteration   2: 6.138 ops/ms
# Warmup Iteration   3: 7.654 ops/ms
Iteration   1: 7.799 ops/ms
Iteration   2: 7.819 ops/ms
Iteration   3: 8.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.938 ±(99.9%) 4.062 ops/ms [Average]
  (min, avg, max) = (7.799, 7.938, 8.194), stdev = 0.223
  CI (99.9%): [3.876, 11.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.059 ops/ms
# Warmup Iteration   2: 5.753 ops/ms
# Warmup Iteration   3: 7.314 ops/ms
Iteration   1: 7.537 ops/ms
Iteration   2: 7.134 ops/ms
Iteration   3: 7.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.370 ±(99.9%) 3.824 ops/ms [Average]
  (min, avg, max) = (7.134, 7.370, 7.537), stdev = 0.210
  CI (99.9%): [3.546, 11.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.911 ops/ms
# Warmup Iteration   2: 5.351 ops/ms
# Warmup Iteration   3: 6.324 ops/ms
Iteration   1: 6.516 ops/ms
Iteration   2: 6.316 ops/ms
Iteration   3: 6.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.391 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (6.316, 6.391, 6.516), stdev = 0.109
  CI (99.9%): [4.397, 8.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 13.825 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.738 ±(99.9%) 0.004 ms/op
Iteration   1: 4.307 ±(99.9%) 0.005 ms/op
Iteration   2: 4.246 ±(99.9%) 0.011 ms/op
Iteration   3: 4.227 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.260 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (4.227, 4.260, 4.307), stdev = 0.042
  CI (99.9%): [3.498, 5.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.835 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.913 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.008 ms/op
Iteration   1: 4.010 ±(99.9%) 0.006 ms/op
Iteration   2: 3.955 ±(99.9%) 0.009 ms/op
Iteration   3: 3.953 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.973 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (3.953, 3.973, 4.010), stdev = 0.032
  CI (99.9%): [3.380, 4.566] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.570 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.078 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.006 ms/op
Iteration   1: 4.396 ±(99.9%) 0.005 ms/op
Iteration   2: 4.234 ±(99.9%) 0.004 ms/op
Iteration   3: 4.198 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.276 ±(99.9%) 1.921 ms/op [Average]
  (min, avg, max) = (4.198, 4.276, 4.396), stdev = 0.105
  CI (99.9%): [2.355, 6.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.972 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.693 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.056 ±(99.9%) 0.008 ms/op
Iteration   1: 4.882 ±(99.9%) 0.010 ms/op
Iteration   2: 4.867 ±(99.9%) 0.012 ms/op
Iteration   3: 4.840 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.863 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (4.840, 4.863, 4.882), stdev = 0.021
  CI (99.9%): [4.477, 5.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.029 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.748 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.666 ±(99.9%) 0.020 ms/op
Iteration   1: 4.165 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  14.673 ms/op
                 createUser·p0.9999: 26.290 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   2: 4.231 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.991 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  25.504 ms/op
                 createUser·p0.9999: 30.381 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   3: 4.286 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.749 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.857 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  18.219 ms/op
                 createUser·p0.9999: 31.228 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 227120
  mean =      4.227 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 271 
    [ 2.500,  5.000) = 205732 
    [ 5.000,  7.500) = 17794 
    [ 7.500, 10.000) = 2159 
    [10.000, 12.500) = 704 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     19.318 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     32.473 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.563 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 4.744 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.015 ms/op
Iteration   1: 4.000 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.615 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  10.820 ms/op
                 existUser·p0.9999: 26.740 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   2: 4.080 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   9.191 ms/op
                 existUser·p0.999:  16.452 ms/op
                 existUser·p0.9999: 27.694 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.954 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  13.238 ms/op
                 existUser·p0.9999: 31.192 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239128
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 231 
    [ 2.500,  5.000) = 224651 
    [ 5.000,  7.500) = 11206 
    [ 7.500, 10.000) = 2095 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     14.554 ms/op
     p(99.9900) =     29.401 ms/op
     p(99.9990) =     31.630 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.636 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.424 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.013 ms/op
Iteration   1: 4.161 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  15.591 ms/op
                 getUser·p0.9999: 25.437 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 4.098 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   8.102 ms/op
                 getUser·p0.999:  16.744 ms/op
                 getUser·p0.9999: 27.581 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   3: 4.072 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  16.708 ms/op
                 getUser·p0.9999: 31.406 ms/op
                 getUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233429
  mean =      4.110 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 220227 
    [ 5.000,  7.500) = 10129 
    [ 7.500, 10.000) = 2156 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     16.148 ms/op
     p(99.9900) =     30.243 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.755 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.706 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.082 ±(99.9%) 0.020 ms/op
Iteration   1: 4.965 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.382 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  26.562 ms/op
                 listUser·p0.9999: 30.558 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   2: 4.993 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.695 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  19.398 ms/op
                 listUser·p0.9999: 26.306 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   3: 4.920 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  18.817 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193362
  mean =      4.959 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 131167 
    [ 5.000,  7.500) = 56361 
    [ 7.500, 10.000) = 4272 
    [10.000, 12.500) = 697 
    [12.500, 15.000) = 303 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.146 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     20.966 ms/op
     p(99.9900) =     28.868 ms/op
     p(99.9990) =     31.070 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.703 ± 4.279  ops/ms
ClientPb.existUser                       thrpt       3   7.938 ± 4.062  ops/ms
ClientPb.getUser                         thrpt       3   7.370 ± 3.824  ops/ms
ClientPb.listUser                        thrpt       3   6.391 ± 1.994  ops/ms
ClientPb.createUser                       avgt       3   4.260 ± 0.763   ms/op
ClientPb.existUser                        avgt       3   3.973 ± 0.593   ms/op
ClientPb.getUser                          avgt       3   4.276 ± 1.921   ms/op
ClientPb.listUser                         avgt       3   4.863 ± 0.386   ms/op
ClientPb.createUser                     sample  227120   4.227 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.282           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.318           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.573           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.834           ms/op
ClientPb.existUser                      sample  239128   4.011 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.696           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.177           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.987           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.554           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.401           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.818           ms/op
ClientPb.getUser                        sample  233429   4.110 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.384           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.045           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.148           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.243           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.244           ms/op
ClientPb.listUser                       sample  193362   4.959 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.146           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.355           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.966           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.868           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.080           ms/op
