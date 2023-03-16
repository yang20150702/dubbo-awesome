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
# Warmup Iteration   1: 2.688 ops/ms
# Warmup Iteration   2: 6.742 ops/ms
# Warmup Iteration   3: 9.153 ops/ms
Iteration   1: 9.825 ops/ms
Iteration   2: 9.966 ops/ms
Iteration   3: 9.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.862 ±(99.9%) 1.676 ops/ms [Average]
  (min, avg, max) = (9.794, 9.862, 9.966), stdev = 0.092
  CI (99.9%): [8.186, 11.538] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.780 ops/ms
# Warmup Iteration   2: 9.660 ops/ms
# Warmup Iteration   3: 10.637 ops/ms
Iteration   1: 10.432 ops/ms
Iteration   2: 10.174 ops/ms
Iteration   3: 10.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.316 ±(99.9%) 2.390 ops/ms [Average]
  (min, avg, max) = (10.174, 10.316, 10.432), stdev = 0.131
  CI (99.9%): [7.927, 12.706] (assumes normal distribution)


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
# Warmup Iteration   1: 3.726 ops/ms
# Warmup Iteration   2: 9.230 ops/ms
# Warmup Iteration   3: 9.481 ops/ms
Iteration   1: 10.102 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.222 ±(99.9%) 2.429 ops/ms [Average]
  (min, avg, max) = (10.102, 10.222, 10.365), stdev = 0.133
  CI (99.9%): [7.792, 12.651] (assumes normal distribution)


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
# Warmup Iteration   1: 3.417 ops/ms
# Warmup Iteration   2: 7.646 ops/ms
# Warmup Iteration   3: 8.177 ops/ms
Iteration   1: 8.541 ops/ms
Iteration   2: 8.615 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.575 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (8.541, 8.575, 8.615), stdev = 0.037
  CI (99.9%): [7.892, 9.257] (assumes normal distribution)


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
# Warmup Iteration   1: 8.304 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.432 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.007 ms/op
Iteration   1: 3.238 ±(99.9%) 0.008 ms/op
Iteration   2: 3.263 ±(99.9%) 0.005 ms/op
Iteration   3: 3.280 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.260 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.238, 3.260, 3.280), stdev = 0.021
  CI (99.9%): [2.873, 3.648] (assumes normal distribution)


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
# Warmup Iteration   1: 8.077 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.004 ms/op
Iteration   1: 3.148 ±(99.9%) 0.007 ms/op
Iteration   2: 3.171 ±(99.9%) 0.004 ms/op
Iteration   3: 2.949 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.089 ±(99.9%) 2.222 ms/op [Average]
  (min, avg, max) = (2.949, 3.089, 3.171), stdev = 0.122
  CI (99.9%): [0.867, 5.311] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.290 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.004 ms/op
Iteration   1: 3.277 ±(99.9%) 0.007 ms/op
Iteration   2: 3.180 ±(99.9%) 0.009 ms/op
Iteration   3: 3.161 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.206 ±(99.9%) 1.138 ms/op [Average]
  (min, avg, max) = (3.161, 3.206, 3.277), stdev = 0.062
  CI (99.9%): [2.069, 4.344] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.320 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.004 ms/op
Iteration   1: 3.587 ±(99.9%) 0.011 ms/op
Iteration   2: 3.615 ±(99.9%) 0.011 ms/op
Iteration   3: 3.679 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.627 ±(99.9%) 0.861 ms/op [Average]
  (min, avg, max) = (3.587, 3.627, 3.679), stdev = 0.047
  CI (99.9%): [2.766, 4.488] (assumes normal distribution)


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
# Warmup Iteration   1: 8.003 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.008 ms/op
Iteration   1: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 22.482 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.187 ms/op
                 createUser·p0.999:  13.211 ms/op
                 createUser·p0.9999: 18.832 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303581
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12147 
    [ 2.500,  5.000) = 285741 
    [ 5.000,  7.500) = 4799 
    [ 7.500, 10.000) = 442 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 194 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     15.789 ms/op
     p(99.9900) =     21.091 ms/op
     p(99.9990) =     23.410 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 6.750 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.009 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  11.631 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 26.542 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.302 ms/op
                 existUser·p0.99:   5.844 ms/op
                 existUser·p0.999:  12.566 ms/op
                 existUser·p0.9999: 20.987 ms/op
                 existUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303426
  mean =      3.162 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13665 
    [ 2.500,  5.000) = 284828 
    [ 5.000,  7.500) = 4115 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     11.946 ms/op
     p(99.9900) =     25.089 ms/op
     p(99.9990) =     26.999 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 8.755 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
Iteration   1: 3.149 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  16.031 ms/op
                 getUser·p0.9999: 19.956 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  10.566 ms/op
                 getUser·p0.9999: 24.886 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.275 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.269 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  14.603 ms/op
                 getUser·p0.9999: 21.667 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301954
  mean =      3.177 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12027 
    [ 2.500,  5.000) = 283544 
    [ 5.000,  7.500) = 5463 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.269 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     14.861 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.919 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.265 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.011 ms/op
Iteration   1: 3.704 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  16.059 ms/op
                 listUser·p0.9999: 21.847 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 3.776 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 16.056 ms/op
                 listUser·p1.00:   16.138 ms/op

Iteration   3: 3.776 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.407 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255772
  mean =      3.752 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 246657 
    [ 5.000,  7.500) = 7234 
    [ 7.500, 10.000) = 1073 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     15.175 ms/op
     p(99.9900) =     20.737 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.862 ± 1.676  ops/ms
ClientPb.existUser                       thrpt       3  10.316 ± 2.390  ops/ms
ClientPb.getUser                         thrpt       3  10.222 ± 2.429  ops/ms
ClientPb.listUser                        thrpt       3   8.575 ± 0.683  ops/ms
ClientPb.createUser                       avgt       3   3.260 ± 0.388   ms/op
ClientPb.existUser                        avgt       3   3.089 ± 2.222   ms/op
ClientPb.getUser                          avgt       3   3.206 ± 1.138   ms/op
ClientPb.listUser                         avgt       3   3.627 ± 0.861   ms/op
ClientPb.createUser                     sample  303581   3.161 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.543           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.789           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.091           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.822           ms/op
ClientPb.existUser                      sample  303426   3.162 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.862           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.946           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.089           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.132           ms/op
ClientPb.getUser                        sample  301954   3.177 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.269           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.861           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.790           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.771           ms/op
ClientPb.listUser                       sample  255772   3.752 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.337           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.737           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.938           ms/op
