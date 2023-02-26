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
# Warmup Iteration   1: 2.585 ops/ms
# Warmup Iteration   2: 6.279 ops/ms
# Warmup Iteration   3: 9.600 ops/ms
Iteration   1: 9.734 ops/ms
Iteration   2: 10.213 ops/ms
Iteration   3: 9.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.938 ±(99.9%) 4.512 ops/ms [Average]
  (min, avg, max) = (9.734, 9.938, 10.213), stdev = 0.247
  CI (99.9%): [5.426, 14.451] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.607 ops/ms
# Warmup Iteration   2: 9.248 ops/ms
# Warmup Iteration   3: 10.332 ops/ms
Iteration   1: 10.087 ops/ms
Iteration   2: 10.287 ops/ms
Iteration   3: 10.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.142 ±(99.9%) 2.305 ops/ms [Average]
  (min, avg, max) = (10.053, 10.142, 10.287), stdev = 0.126
  CI (99.9%): [7.837, 12.447] (assumes normal distribution)


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
# Warmup Iteration   1: 3.239 ops/ms
# Warmup Iteration   2: 8.123 ops/ms
# Warmup Iteration   3: 9.881 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 9.897 ops/ms
Iteration   3: 9.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.087 ±(99.9%) 4.861 ops/ms [Average]
  (min, avg, max) = (9.897, 10.087, 10.392), stdev = 0.266
  CI (99.9%): [5.227, 14.948] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.205 ops/ms
# Warmup Iteration   2: 7.925 ops/ms
# Warmup Iteration   3: 8.465 ops/ms
Iteration   1: 8.706 ops/ms
Iteration   2: 8.726 ops/ms
Iteration   3: 8.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.657 ±(99.9%) 1.892 ops/ms [Average]
  (min, avg, max) = (8.537, 8.657, 8.726), stdev = 0.104
  CI (99.9%): [6.765, 10.548] (assumes normal distribution)


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
# Warmup Iteration   1: 7.818 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.004 ms/op
Iteration   1: 3.363 ±(99.9%) 0.008 ms/op
Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
Iteration   3: 3.078 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.187 ±(99.9%) 2.811 ms/op [Average]
  (min, avg, max) = (3.078, 3.187, 3.363), stdev = 0.154
  CI (99.9%): [0.376, 5.998] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.775 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 3.047 ±(99.9%) 0.004 ms/op
Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
Iteration   3: 2.995 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.017 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (2.995, 3.017, 3.047), stdev = 0.027
  CI (99.9%): [2.532, 3.502] (assumes normal distribution)


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
# Warmup Iteration   1: 8.634 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.485 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.003 ms/op
Iteration   1: 3.214 ±(99.9%) 0.004 ms/op
Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
Iteration   3: 3.255 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.223 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.201, 3.223, 3.255), stdev = 0.028
  CI (99.9%): [2.710, 3.736] (assumes normal distribution)


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
# Warmup Iteration   1: 8.952 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.005 ms/op
Iteration   1: 3.806 ±(99.9%) 0.007 ms/op
Iteration   2: 3.679 ±(99.9%) 0.008 ms/op
Iteration   3: 3.741 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.742 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (3.679, 3.742, 3.806), stdev = 0.063
  CI (99.9%): [2.584, 4.900] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.294 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.820 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  9.500 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.283 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.466 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299857
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18896 
    [ 2.500,  5.000) = 274036 
    [ 5.000,  7.500) = 6141 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     16.520 ms/op
     p(99.9900) =     23.528 ms/op
     p(99.9990) =     26.444 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.971 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  10.240 ms/op
                 existUser·p0.9999: 20.399 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.099 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  19.548 ms/op
                 existUser·p0.9999: 23.474 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  8.454 ms/op
                 existUser·p0.9999: 23.647 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305088
  mean =      3.145 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25807 
    [ 2.500,  5.000) = 273404 
    [ 5.000,  7.500) = 5236 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     15.200 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 8.050 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.009 ms/op
Iteration   1: 3.240 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.171 ms/op
                 getUser·p0.999:  15.258 ms/op
                 getUser·p0.9999: 28.394 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 23.653 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  13.502 ms/op
                 getUser·p0.9999: 21.326 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302170
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16381 
    [ 2.500,  5.000) = 279634 
    [ 5.000,  7.500) = 5148 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     16.346 ms/op
     p(99.9900) =     25.353 ms/op
     p(99.9990) =     28.867 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 8.872 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.012 ms/op
Iteration   1: 3.715 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.360 ms/op
                 listUser·p0.9999: 21.947 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 3.726 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 3.773 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 17.024 ms/op
                 listUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256662
  mean =      3.738 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 249953 
    [ 5.000,  7.500) = 4877 
    [ 7.500, 10.000) = 1101 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.790 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.456 ms/op
     p(99.9900) =     21.092 ms/op
     p(99.9990) =     24.000 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.938 ± 4.512  ops/ms
ClientPb.existUser                       thrpt       3  10.142 ± 2.305  ops/ms
ClientPb.getUser                         thrpt       3  10.087 ± 4.861  ops/ms
ClientPb.listUser                        thrpt       3   8.657 ± 1.892  ops/ms
ClientPb.createUser                       avgt       3   3.187 ± 2.811   ms/op
ClientPb.existUser                        avgt       3   3.017 ± 0.485   ms/op
ClientPb.getUser                          avgt       3   3.223 ± 0.513   ms/op
ClientPb.listUser                         avgt       3   3.742 ± 1.158   ms/op
ClientPb.createUser                     sample  299857   3.200 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.008           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.528           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  305088   3.145 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.968           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.265           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.904           ms/op
ClientPb.getUser                        sample  302170   3.176 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.634           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.346           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.353           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.229           ms/op
ClientPb.listUser                       sample  256662   3.738 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.790           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.456           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.092           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.445           ms/op
