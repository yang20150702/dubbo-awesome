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
# Warmup Iteration   1: 0.942 ops/ms
# Warmup Iteration   2: 2.106 ops/ms
# Warmup Iteration   3: 4.608 ops/ms
Iteration   1: 5.079 ops/ms
Iteration   2: 5.164 ops/ms
Iteration   3: 5.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.161 ±(99.9%) 1.457 ops/ms [Average]
  (min, avg, max) = (5.079, 5.161, 5.239), stdev = 0.080
  CI (99.9%): [3.703, 6.618] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.581 ops/ms
# Warmup Iteration   2: 4.182 ops/ms
# Warmup Iteration   3: 5.319 ops/ms
Iteration   1: 5.618 ops/ms
Iteration   2: 5.492 ops/ms
Iteration   3: 5.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.672 ±(99.9%) 3.869 ops/ms [Average]
  (min, avg, max) = (5.492, 5.672, 5.905), stdev = 0.212
  CI (99.9%): [1.802, 9.541] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.465 ops/ms
# Warmup Iteration   2: 4.192 ops/ms
# Warmup Iteration   3: 5.165 ops/ms
Iteration   1: 5.487 ops/ms
Iteration   2: 5.413 ops/ms
Iteration   3: 5.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.381 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (5.243, 5.381, 5.487), stdev = 0.125
  CI (99.9%): [3.098, 7.665] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.422 ops/ms
# Warmup Iteration   2: 3.677 ops/ms
# Warmup Iteration   3: 4.554 ops/ms
Iteration   1: 4.595 ops/ms
Iteration   2: 4.783 ops/ms
Iteration   3: 4.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.698 ±(99.9%) 1.744 ops/ms [Average]
  (min, avg, max) = (4.595, 4.698, 4.783), stdev = 0.096
  CI (99.9%): [2.954, 6.442] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 19.800 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 7.570 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.005 ±(99.9%) 0.010 ms/op
Iteration   1: 5.689 ±(99.9%) 0.022 ms/op
Iteration   2: 5.834 ±(99.9%) 0.009 ms/op
Iteration   3: 6.236 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.920 ±(99.9%) 5.173 ms/op [Average]
  (min, avg, max) = (5.689, 5.920, 6.236), stdev = 0.284
  CI (99.9%): [0.747, 11.093] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.302 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.955 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.798 ±(99.9%) 0.012 ms/op
Iteration   1: 6.107 ±(99.9%) 0.014 ms/op
Iteration   2: 6.271 ±(99.9%) 0.007 ms/op
Iteration   3: 6.078 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.152 ±(99.9%) 1.899 ms/op [Average]
  (min, avg, max) = (6.078, 6.152, 6.271), stdev = 0.104
  CI (99.9%): [4.253, 8.051] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.389 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.421 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.109 ±(99.9%) 0.011 ms/op
Iteration   1: 6.336 ±(99.9%) 0.011 ms/op
Iteration   2: 6.040 ±(99.9%) 0.013 ms/op
Iteration   3: 6.430 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.268 ±(99.9%) 3.715 ms/op [Average]
  (min, avg, max) = (6.040, 6.268, 6.430), stdev = 0.204
  CI (99.9%): [2.554, 9.983] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.089 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 8.208 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 7.451 ±(99.9%) 0.012 ms/op
Iteration   1: 7.298 ±(99.9%) 0.016 ms/op
Iteration   2: 7.343 ±(99.9%) 0.013 ms/op
Iteration   3: 7.272 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.304 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (7.272, 7.304, 7.343), stdev = 0.036
  CI (99.9%): [6.648, 7.960] (assumes normal distribution)


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
# Warmup Iteration   1: 21.268 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 8.632 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 6.819 ±(99.9%) 0.035 ms/op
Iteration   1: 6.370 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.757 ms/op
                 createUser·p0.50:   6.021 ms/op
                 createUser·p0.90:   8.348 ms/op
                 createUser·p0.95:   9.273 ms/op
                 createUser·p0.99:   12.239 ms/op
                 createUser·p0.999:  19.753 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 6.219 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.458 ms/op
                 createUser·p0.50:   5.841 ms/op
                 createUser·p0.90:   7.766 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   11.878 ms/op
                 createUser·p0.999:  27.369 ms/op
                 createUser·p0.9999: 38.599 ms/op
                 createUser·p1.00:   41.681 ms/op

Iteration   3: 6.610 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   2.515 ms/op
                 createUser·p0.50:   6.242 ms/op
                 createUser·p0.90:   8.454 ms/op
                 createUser·p0.95:   9.568 ms/op
                 createUser·p0.99:   13.992 ms/op
                 createUser·p0.999:  32.297 ms/op
                 createUser·p0.9999: 37.868 ms/op
                 createUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 149911
  mean =      6.396 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 20589 
    [ 5.000, 10.000) = 124971 
    [10.000, 15.000) = 3562 
    [15.000, 20.000) = 538 
    [20.000, 25.000) = 86 
    [25.000, 30.000) = 67 
    [30.000, 35.000) = 49 
    [35.000, 40.000) = 46 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.458 ms/op
     p(50.0000) =      6.062 ms/op
     p(90.0000) =      8.217 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     25.693 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     41.452 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.052 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 7.243 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.940 ±(99.9%) 0.022 ms/op
Iteration   1: 5.894 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.466 ms/op
                 existUser·p0.50:   5.431 ms/op
                 existUser·p0.90:   7.422 ms/op
                 existUser·p0.95:   8.782 ms/op
                 existUser·p0.99:   12.648 ms/op
                 existUser·p0.999:  22.305 ms/op
                 existUser·p0.9999: 29.220 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   2: 5.634 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.494 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   7.004 ms/op
                 existUser·p0.95:   8.143 ms/op
                 existUser·p0.99:   11.420 ms/op
                 existUser·p0.999:  26.976 ms/op
                 existUser·p0.9999: 30.408 ms/op
                 existUser·p1.00:   31.556 ms/op

Iteration   3: 6.218 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   5.939 ms/op
                 existUser·p0.90:   7.954 ms/op
                 existUser·p0.95:   8.782 ms/op
                 existUser·p0.99:   12.321 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 34.463 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 162473
  mean =      5.906 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 48705 
    [ 5.000,  7.500) = 96883 
    [ 7.500, 10.000) = 13103 
    [10.000, 12.500) = 2314 
    [12.500, 15.000) = 752 
    [15.000, 17.500) = 306 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     12.190 ms/op
     p(99.9000) =     25.133 ms/op
     p(99.9900) =     33.456 ms/op
     p(99.9990) =     34.914 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.915 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 7.864 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.397 ±(99.9%) 0.027 ms/op
Iteration   1: 5.977 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   3.011 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   8.782 ms/op
                 getUser·p0.99:   12.386 ms/op
                 getUser·p0.999:  20.213 ms/op
                 getUser·p0.9999: 29.873 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 6.328 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.564 ms/op
                 getUser·p0.50:   5.841 ms/op
                 getUser·p0.90:   8.569 ms/op
                 getUser·p0.95:   9.470 ms/op
                 getUser·p0.99:   13.124 ms/op
                 getUser·p0.999:  29.422 ms/op
                 getUser·p0.9999: 33.937 ms/op
                 getUser·p1.00:   34.996 ms/op

Iteration   3: 6.170 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.757 ms/op
                 getUser·p0.50:   5.816 ms/op
                 getUser·p0.90:   7.717 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   11.616 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 31.160 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155926
  mean =      6.155 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 28682 
    [ 5.000,  7.500) = 106932 
    [ 7.500, 10.000) = 15961 
    [10.000, 12.500) = 2802 
    [12.500, 15.000) = 806 
    [15.000, 17.500) = 336 
    [17.500, 20.000) = 191 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.564 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      7.922 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     23.006 ms/op
     p(99.9900) =     32.388 ms/op
     p(99.9990) =     34.630 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 22.512 ±(99.9%) 0.391 ms/op
# Warmup Iteration   2: 9.634 ±(99.9%) 0.084 ms/op
# Warmup Iteration   3: 7.561 ±(99.9%) 0.039 ms/op
Iteration   1: 7.489 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.727 ms/op
                 listUser·p0.50:   7.234 ms/op
                 listUser·p0.90:   9.683 ms/op
                 listUser·p0.95:   10.797 ms/op
                 listUser·p0.99:   14.254 ms/op
                 listUser·p0.999:  26.583 ms/op
                 listUser·p0.9999: 31.831 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   2: 7.219 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.285 ms/op
                 listUser·p0.50:   6.947 ms/op
                 listUser·p0.90:   8.929 ms/op
                 listUser·p0.95:   10.058 ms/op
                 listUser·p0.99:   13.304 ms/op
                 listUser·p0.999:  28.334 ms/op
                 listUser·p0.9999: 31.780 ms/op
                 listUser·p1.00:   33.522 ms/op

Iteration   3: 7.368 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.396 ms/op
                 listUser·p0.50:   7.053 ms/op
                 listUser·p0.90:   9.028 ms/op
                 listUser·p0.95:   10.109 ms/op
                 listUser·p0.99:   13.354 ms/op
                 listUser·p0.999:  32.506 ms/op
                 listUser·p0.9999: 36.875 ms/op
                 listUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 130446
  mean =      7.357 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1184 
    [ 5.000,  7.500) = 81476 
    [ 7.500, 10.000) = 39872 
    [10.000, 12.500) = 5839 
    [12.500, 15.000) = 1176 
    [15.000, 17.500) = 364 
    [17.500, 20.000) = 193 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      3.285 ms/op
     p(50.0000) =      7.070 ms/op
     p(90.0000) =      9.208 ms/op
     p(95.0000) =     10.355 ms/op
     p(99.0000) =     13.795 ms/op
     p(99.9000) =     29.131 ms/op
     p(99.9900) =     35.446 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.161 ± 1.457  ops/ms
ClientPb.existUser                       thrpt       3   5.672 ± 3.869  ops/ms
ClientPb.getUser                         thrpt       3   5.381 ± 2.284  ops/ms
ClientPb.listUser                        thrpt       3   4.698 ± 1.744  ops/ms
ClientPb.createUser                       avgt       3   5.920 ± 5.173   ms/op
ClientPb.existUser                        avgt       3   6.152 ± 1.899   ms/op
ClientPb.getUser                          avgt       3   6.268 ± 3.715   ms/op
ClientPb.listUser                         avgt       3   7.304 ± 0.656   ms/op
ClientPb.createUser                     sample  149911   6.396 ± 0.016   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.458           ms/op
ClientPb.createUser:createUser·p0.50    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.90    sample           8.217           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.191           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.730           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.693           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.683           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.681           ms/op
ClientPb.existUser                      sample  162473   5.906 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.624           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.545           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.618           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.190           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.133           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.456           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.996           ms/op
ClientPb.getUser                        sample  155926   6.155 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.726           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.922           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.126           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.485           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.006           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.388           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.996           ms/op
ClientPb.listUser                       sample  130446   7.357 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.285           ms/op
ClientPb.listUser:listUser·p0.50        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.208           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.355           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.795           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.131           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.446           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.011           ms/op
