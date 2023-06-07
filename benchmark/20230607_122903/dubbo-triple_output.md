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
# Warmup Iteration   1: 2.281 ops/ms
# Warmup Iteration   2: 5.515 ops/ms
# Warmup Iteration   3: 8.179 ops/ms
Iteration   1: 8.532 ops/ms
Iteration   2: 8.913 ops/ms
Iteration   3: 9.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.917 ±(99.9%) 7.069 ops/ms [Average]
  (min, avg, max) = (8.532, 8.917, 9.307), stdev = 0.387
  CI (99.9%): [1.849, 15.986] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.091 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.409 ops/ms
Iteration   1: 9.804 ops/ms
Iteration   2: 9.584 ops/ms
Iteration   3: 9.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.722 ±(99.9%) 2.194 ops/ms [Average]
  (min, avg, max) = (9.584, 9.722, 9.804), stdev = 0.120
  CI (99.9%): [7.528, 11.916] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 8.613 ops/ms
# Warmup Iteration   3: 9.134 ops/ms
Iteration   1: 9.325 ops/ms
Iteration   2: 9.320 ops/ms
Iteration   3: 9.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.272 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (9.170, 9.272, 9.325), stdev = 0.088
  CI (99.9%): [7.666, 10.877] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.926 ops/ms
# Warmup Iteration   2: 7.152 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 7.811 ops/ms
Iteration   2: 7.790 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.896 ±(99.9%) 3.033 ops/ms [Average]
  (min, avg, max) = (7.790, 7.896, 8.088), stdev = 0.166
  CI (99.9%): [4.864, 10.929] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.324 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.004 ms/op
Iteration   1: 3.633 ±(99.9%) 0.006 ms/op
Iteration   2: 3.437 ±(99.9%) 0.006 ms/op
Iteration   3: 3.466 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.512 ±(99.9%) 1.932 ms/op [Average]
  (min, avg, max) = (3.437, 3.512, 3.633), stdev = 0.106
  CI (99.9%): [1.580, 5.444] (assumes normal distribution)


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
# Warmup Iteration   1: 8.285 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.007 ms/op
Iteration   1: 3.260 ±(99.9%) 0.003 ms/op
Iteration   2: 3.388 ±(99.9%) 0.004 ms/op
Iteration   3: 3.521 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.390 ±(99.9%) 2.382 ms/op [Average]
  (min, avg, max) = (3.260, 3.390, 3.521), stdev = 0.131
  CI (99.9%): [1.008, 5.772] (assumes normal distribution)


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
# Warmup Iteration   1: 8.415 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.004 ms/op
Iteration   1: 3.479 ±(99.9%) 0.007 ms/op
Iteration   2: 3.442 ±(99.9%) 0.007 ms/op
Iteration   3: 3.377 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.433 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (3.377, 3.433, 3.479), stdev = 0.051
  CI (99.9%): [2.495, 4.370] (assumes normal distribution)


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
# Warmup Iteration   1: 9.713 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.008 ms/op
Iteration   1: 4.105 ±(99.9%) 0.008 ms/op
Iteration   2: 4.026 ±(99.9%) 0.007 ms/op
Iteration   3: 4.002 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.044 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (4.002, 4.044, 4.105), stdev = 0.054
  CI (99.9%): [3.055, 5.033] (assumes normal distribution)


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
# Warmup Iteration   1: 8.149 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
Iteration   1: 3.550 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.751 ms/op
                 createUser·p0.9999: 23.297 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.516 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  21.539 ms/op
                 createUser·p0.9999: 24.966 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.485 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  26.121 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273005
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7173 
    [ 2.500,  5.000) = 258699 
    [ 5.000,  7.500) = 5907 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     29.068 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 8.054 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.010 ms/op
Iteration   1: 3.431 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.740 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   2: 3.446 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  25.272 ms/op
                 existUser·p0.9999: 29.464 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   3: 3.387 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  13.369 ms/op
                 existUser·p0.9999: 31.181 ms/op
                 existUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280380
  mean =      3.421 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8760 
    [ 2.500,  5.000) = 263639 
    [ 5.000,  7.500) = 6524 
    [ 7.500, 10.000) = 880 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.424 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     30.245 ms/op
     p(99.9990) =     31.482 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.304 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.012 ms/op
Iteration   1: 3.479 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 24.865 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 3.406 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  21.371 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   3: 3.496 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  20.372 ms/op
                 getUser·p0.9999: 32.506 ms/op
                 getUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277154
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 918 
    [ 2.500,  5.000) = 268519 
    [ 5.000,  7.500) = 6615 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     11.824 ms/op
     p(99.9900) =     31.368 ms/op
     p(99.9990) =     33.118 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 11.091 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.014 ms/op
Iteration   1: 4.206 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  22.016 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   2: 4.056 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  15.991 ms/op
                 listUser·p0.9999: 17.539 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.929 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.153 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236304
  mean =      4.061 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 227959 
    [ 5.000,  7.500) = 6075 
    [ 7.500, 10.000) = 1580 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     25.801 ms/op
     p(99.9990) =     28.369 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.917 ± 7.069  ops/ms
ClientPb.existUser                       thrpt       3   9.722 ± 2.194  ops/ms
ClientPb.getUser                         thrpt       3   9.272 ± 1.606  ops/ms
ClientPb.listUser                        thrpt       3   7.896 ± 3.033  ops/ms
ClientPb.createUser                       avgt       3   3.512 ± 1.932   ms/op
ClientPb.existUser                        avgt       3   3.390 ± 2.382   ms/op
ClientPb.getUser                          avgt       3   3.433 ± 0.937   ms/op
ClientPb.listUser                         avgt       3   4.044 ± 0.989   ms/op
ClientPb.createUser                     sample  273005   3.517 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.133           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.496           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.787           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.622           ms/op
ClientPb.existUser                      sample  280380   3.421 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.444           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.547           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.424           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.245           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.309           ms/op
ClientPb.getUser                        sample  277154   3.459 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.413           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.824           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.368           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.194           ms/op
ClientPb.listUser                       sample  236304   4.061 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.362           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.801           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.803           ms/op
