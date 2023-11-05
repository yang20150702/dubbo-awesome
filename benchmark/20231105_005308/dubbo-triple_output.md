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
# Warmup Iteration   1: 1.152 ops/ms
# Warmup Iteration   2: 2.674 ops/ms
# Warmup Iteration   3: 5.737 ops/ms
Iteration   1: 5.943 ops/ms
Iteration   2: 6.238 ops/ms
Iteration   3: 6.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.118 ±(99.9%) 2.834 ops/ms [Average]
  (min, avg, max) = (5.943, 6.118, 6.238), stdev = 0.155
  CI (99.9%): [3.284, 8.952] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.930 ops/ms
# Warmup Iteration   2: 5.501 ops/ms
# Warmup Iteration   3: 6.335 ops/ms
Iteration   1: 6.558 ops/ms
Iteration   2: 6.401 ops/ms
Iteration   3: 6.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.490 ±(99.9%) 1.470 ops/ms [Average]
  (min, avg, max) = (6.401, 6.490, 6.558), stdev = 0.081
  CI (99.9%): [5.021, 7.960] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.683 ops/ms
# Warmup Iteration   2: 4.771 ops/ms
# Warmup Iteration   3: 5.902 ops/ms
Iteration   1: 5.877 ops/ms
Iteration   2: 5.874 ops/ms
Iteration   3: 6.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.933 ±(99.9%) 1.829 ops/ms [Average]
  (min, avg, max) = (5.874, 5.933, 6.049), stdev = 0.100
  CI (99.9%): [4.105, 7.762] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.846 ops/ms
# Warmup Iteration   2: 4.441 ops/ms
# Warmup Iteration   3: 4.789 ops/ms
Iteration   1: 4.964 ops/ms
Iteration   2: 4.848 ops/ms
Iteration   3: 5.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.957 ±(99.9%) 1.929 ops/ms [Average]
  (min, avg, max) = (4.848, 4.957, 5.060), stdev = 0.106
  CI (99.9%): [3.028, 6.887] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.579 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.247 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.920 ±(99.9%) 0.009 ms/op
Iteration   1: 5.435 ±(99.9%) 0.018 ms/op
Iteration   2: 5.336 ±(99.9%) 0.012 ms/op
Iteration   3: 5.245 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.339 ±(99.9%) 1.726 ms/op [Average]
  (min, avg, max) = (5.245, 5.339, 5.435), stdev = 0.095
  CI (99.9%): [3.613, 7.065] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.290 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.242 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.973 ±(99.9%) 0.008 ms/op
Iteration   1: 5.017 ±(99.9%) 0.010 ms/op
Iteration   2: 4.772 ±(99.9%) 0.014 ms/op
Iteration   3: 4.920 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.903 ±(99.9%) 2.252 ms/op [Average]
  (min, avg, max) = (4.772, 4.903, 5.017), stdev = 0.123
  CI (99.9%): [2.651, 7.154] (assumes normal distribution)


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
# Warmup Iteration   1: 14.340 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.503 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.019 ±(99.9%) 0.006 ms/op
Iteration   1: 4.849 ±(99.9%) 0.011 ms/op
Iteration   2: 4.745 ±(99.9%) 0.015 ms/op
Iteration   3: 4.968 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.854 ±(99.9%) 2.040 ms/op [Average]
  (min, avg, max) = (4.745, 4.854, 4.968), stdev = 0.112
  CI (99.9%): [2.814, 6.894] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.728 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.269 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.730 ±(99.9%) 0.013 ms/op
Iteration   1: 5.745 ±(99.9%) 0.009 ms/op
Iteration   2: 5.591 ±(99.9%) 0.016 ms/op
Iteration   3: 5.631 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.656 ±(99.9%) 1.456 ms/op [Average]
  (min, avg, max) = (5.591, 5.656, 5.745), stdev = 0.080
  CI (99.9%): [4.199, 7.112] (assumes normal distribution)


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
# Warmup Iteration   1: 14.312 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.872 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.283 ±(99.9%) 0.021 ms/op
Iteration   1: 4.962 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.318 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   6.904 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  21.904 ms/op
                 createUser·p0.9999: 28.133 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   2: 5.088 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.154 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.332 ms/op
                 createUser·p0.95:   7.209 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  23.095 ms/op
                 createUser·p0.9999: 31.097 ms/op
                 createUser·p1.00:   31.654 ms/op

Iteration   3: 5.032 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   6.889 ms/op
                 createUser·p0.99:   9.028 ms/op
                 createUser·p0.999:  27.016 ms/op
                 createUser·p0.9999: 32.593 ms/op
                 createUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 190806
  mean =      5.027 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 120130 
    [ 5.000,  7.500) = 64200 
    [ 7.500, 10.000) = 5170 
    [10.000, 12.500) = 591 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     22.013 ms/op
     p(99.9900) =     31.444 ms/op
     p(99.9990) =     33.057 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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
# Warmup Iteration   1: 13.262 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.112 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.801 ±(99.9%) 0.016 ms/op
Iteration   1: 4.678 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.126 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   5.612 ms/op
                 existUser·p0.95:   6.291 ms/op
                 existUser·p0.99:   8.651 ms/op
                 existUser·p0.999:  15.172 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   2: 4.705 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.991 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.669 ms/op
                 existUser·p0.95:   6.275 ms/op
                 existUser·p0.99:   9.110 ms/op
                 existUser·p0.999:  14.552 ms/op
                 existUser·p0.9999: 26.516 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   3: 4.756 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   4.448 ms/op
                 existUser·p0.90:   5.915 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.273 ms/op
                 existUser·p0.999:  18.776 ms/op
                 existUser·p0.9999: 31.490 ms/op
                 existUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 203501
  mean =      4.713 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 173 
    [ 2.500,  5.000) = 154319 
    [ 5.000,  7.500) = 44187 
    [ 7.500, 10.000) = 3496 
    [10.000, 12.500) = 751 
    [12.500, 15.000) = 328 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     15.991 ms/op
     p(99.9900) =     28.769 ms/op
     p(99.9990) =     32.174 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 13.936 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.507 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.095 ±(99.9%) 0.018 ms/op
Iteration   1: 5.099 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.847 ms/op
                 getUser·p0.50:   4.776 ms/op
                 getUser·p0.90:   6.013 ms/op
                 getUser·p0.95:   7.447 ms/op
                 getUser·p0.99:   11.862 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 26.688 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 4.880 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   4.735 ms/op
                 getUser·p0.90:   5.767 ms/op
                 getUser·p0.95:   6.283 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  18.470 ms/op
                 getUser·p0.9999: 34.985 ms/op
                 getUser·p1.00:   36.438 ms/op

Iteration   3: 5.111 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.878 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.095 ms/op
                 getUser·p0.95:   7.086 ms/op
                 getUser·p0.99:   10.027 ms/op
                 getUser·p0.999:  23.411 ms/op
                 getUser·p0.9999: 28.369 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 190673
  mean =      5.028 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 119586 
    [ 5.000,  7.500) = 64383 
    [ 7.500, 10.000) = 4527 
    [10.000, 12.500) = 1390 
    [12.500, 15.000) = 384 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.878 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     32.766 ms/op
     p(99.9990) =     36.022 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 16.541 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 6.800 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.884 ±(99.9%) 0.021 ms/op
Iteration   1: 5.867 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.781 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.012 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  26.149 ms/op
                 listUser·p0.9999: 29.837 ms/op
                 listUser·p1.00:   32.276 ms/op

Iteration   2: 5.845 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  26.006 ms/op
                 listUser·p0.9999: 28.886 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   3: 5.787 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   6.824 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   10.753 ms/op
                 listUser·p0.999:  19.947 ms/op
                 listUser·p0.9999: 22.524 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164489
  mean =      5.833 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 26684 
    [ 5.000,  7.500) = 126947 
    [ 7.500, 10.000) = 8169 
    [10.000, 12.500) = 1648 
    [12.500, 15.000) = 380 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     24.593 ms/op
     p(99.9900) =     29.083 ms/op
     p(99.9990) =     32.044 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.118 ± 2.834  ops/ms
ClientPb.existUser                       thrpt       3   6.490 ± 1.470  ops/ms
ClientPb.getUser                         thrpt       3   5.933 ± 1.829  ops/ms
ClientPb.listUser                        thrpt       3   4.957 ± 1.929  ops/ms
ClientPb.createUser                       avgt       3   5.339 ± 1.726   ms/op
ClientPb.existUser                        avgt       3   4.903 ± 2.252   ms/op
ClientPb.getUser                          avgt       3   4.854 ± 2.040   ms/op
ClientPb.listUser                         avgt       3   5.656 ± 1.456   ms/op
ClientPb.createUser                     sample  190806   5.027 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.154           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.160           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.021           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.273           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.013           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.444           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.325           ms/op
ClientPb.existUser                      sample  203501   4.713 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.946           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.011           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.991           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.769           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.735           ms/op
ClientPb.getUser                        sample  190673   5.028 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.878           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.273           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.840           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.766           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438           ms/op
ClientPb.listUser                       sample  164489   5.833 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.419           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.897           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.092           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.593           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.083           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.276           ms/op
