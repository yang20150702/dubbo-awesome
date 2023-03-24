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
# Warmup Iteration   1: 2.631 ops/ms
# Warmup Iteration   2: 6.471 ops/ms
# Warmup Iteration   3: 9.027 ops/ms
Iteration   1: 9.913 ops/ms
Iteration   2: 9.700 ops/ms
Iteration   3: 9.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.790 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (9.700, 9.790, 9.913), stdev = 0.110
  CI (99.9%): [7.777, 11.803] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ops/ms
# Warmup Iteration   2: 9.889 ops/ms
# Warmup Iteration   3: 10.268 ops/ms
Iteration   1: 10.626 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.432 ±(99.9%) 3.060 ops/ms [Average]
  (min, avg, max) = (10.330, 10.432, 10.626), stdev = 0.168
  CI (99.9%): [7.373, 13.492] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ops/ms
# Warmup Iteration   2: 9.466 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 10.152 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.242 ±(99.9%) 1.734 ops/ms [Average]
  (min, avg, max) = (10.152, 10.242, 10.341), stdev = 0.095
  CI (99.9%): [8.509, 11.976] (assumes normal distribution)


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
# Warmup Iteration   1: 3.868 ops/ms
# Warmup Iteration   2: 8.244 ops/ms
# Warmup Iteration   3: 8.616 ops/ms
Iteration   1: 8.683 ops/ms
Iteration   2: 8.659 ops/ms
Iteration   3: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.675 ±(99.9%) 0.257 ops/ms [Average]
  (min, avg, max) = (8.659, 8.675, 8.683), stdev = 0.014
  CI (99.9%): [8.418, 8.932] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.492 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.007 ms/op
Iteration   1: 3.255 ±(99.9%) 0.007 ms/op
Iteration   2: 3.173 ±(99.9%) 0.005 ms/op
Iteration   3: 3.187 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (3.173, 3.205, 3.255), stdev = 0.044
  CI (99.9%): [2.401, 4.009] (assumes normal distribution)


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
# Warmup Iteration   1: 6.961 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.003 ms/op
Iteration   1: 3.116 ±(99.9%) 0.007 ms/op
Iteration   2: 2.932 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.008 ±(99.9%) 1.754 ms/op [Average]
  (min, avg, max) = (2.932, 3.008, 3.116), stdev = 0.096
  CI (99.9%): [1.254, 4.761] (assumes normal distribution)


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
# Warmup Iteration   1: 6.395 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.005 ms/op
Iteration   3: 3.184 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.133 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.093, 3.133, 3.184), stdev = 0.047
  CI (99.9%): [2.280, 3.986] (assumes normal distribution)


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
# Warmup Iteration   1: 8.521 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.006 ms/op
Iteration   1: 3.638 ±(99.9%) 0.011 ms/op
Iteration   2: 3.691 ±(99.9%) 0.008 ms/op
Iteration   3: 3.695 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.675 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.638, 3.675, 3.695), stdev = 0.032
  CI (99.9%): [3.094, 4.256] (assumes normal distribution)


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
# Warmup Iteration   1: 7.864 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
Iteration   1: 3.269 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  13.651 ms/op
                 createUser·p0.9999: 25.657 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 25.618 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  15.277 ms/op
                 createUser·p0.9999: 20.594 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294077
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16387 
    [ 2.500,  5.000) = 271489 
    [ 5.000,  7.500) = 5461 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     14.089 ms/op
     p(99.9900) =     25.316 ms/op
     p(99.9990) =     26.282 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 6.984 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 3.075 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 19.490 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  10.470 ms/op
                 existUser·p0.9999: 20.660 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  14.270 ms/op
                 existUser·p0.9999: 19.565 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313683
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21167 
    [ 2.500,  5.000) = 287371 
    [ 5.000,  7.500) = 4482 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 187 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     19.866 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 7.195 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.009 ms/op
Iteration   1: 3.194 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  11.024 ms/op
                 getUser·p0.9999: 18.055 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  9.237 ms/op
                 getUser·p0.9999: 21.226 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  12.890 ms/op
                 getUser·p0.9999: 18.808 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303619
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16507 
    [ 2.500,  5.000) = 280876 
    [ 5.000,  7.500) = 5340 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     12.573 ms/op
     p(99.9900) =     19.911 ms/op
     p(99.9990) =     22.017 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 8.415 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.011 ms/op
Iteration   1: 3.796 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 17.652 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   2: 3.799 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 3.729 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.324 ms/op
                 listUser·p0.999:  13.914 ms/op
                 listUser·p0.9999: 21.444 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254132
  mean =      3.775 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 246645 
    [ 5.000,  7.500) = 5708 
    [ 7.500, 10.000) = 1126 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.790 ± 2.013  ops/ms
ClientPb.existUser                       thrpt       3  10.432 ± 3.060  ops/ms
ClientPb.getUser                         thrpt       3  10.242 ± 1.734  ops/ms
ClientPb.listUser                        thrpt       3   8.675 ± 0.257  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 0.804   ms/op
ClientPb.existUser                        avgt       3   3.008 ± 1.754   ms/op
ClientPb.getUser                          avgt       3   3.133 ± 0.853   ms/op
ClientPb.listUser                         avgt       3   3.675 ± 0.581   ms/op
ClientPb.createUser                     sample  294077   3.260 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.768           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.089           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.316           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.575           ms/op
ClientPb.existUser                      sample  313683   3.060 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.942           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.866           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.004           ms/op
ClientPb.getUser                        sample  303619   3.160 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.897           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.573           ms/op
ClientPb.getUser:getUser·p0.9999        sample          19.911           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.086           ms/op
ClientPb.listUser                       sample  254132   3.775 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.444           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.430           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.953           ms/op
