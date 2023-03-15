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
# Warmup Iteration   1: 2.696 ops/ms
# Warmup Iteration   2: 6.610 ops/ms
# Warmup Iteration   3: 9.298 ops/ms
Iteration   1: 9.883 ops/ms
Iteration   2: 9.994 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.081 ±(99.9%) 4.623 ops/ms [Average]
  (min, avg, max) = (9.883, 10.081, 10.366), stdev = 0.253
  CI (99.9%): [5.458, 14.704] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ops/ms
# Warmup Iteration   2: 9.452 ops/ms
# Warmup Iteration   3: 10.340 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.396 ±(99.9%) 0.718 ops/ms [Average]
  (min, avg, max) = (10.367, 10.396, 10.441), stdev = 0.039
  CI (99.9%): [9.678, 11.114] (assumes normal distribution)


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
# Warmup Iteration   1: 3.577 ops/ms
# Warmup Iteration   2: 9.532 ops/ms
# Warmup Iteration   3: 10.075 ops/ms
Iteration   1: 10.148 ops/ms
Iteration   2: 10.279 ops/ms
Iteration   3: 9.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.995 ±(99.9%) 7.006 ops/ms [Average]
  (min, avg, max) = (9.558, 9.995, 10.279), stdev = 0.384
  CI (99.9%): [2.989, 17.001] (assumes normal distribution)


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
# Warmup Iteration   1: 3.297 ops/ms
# Warmup Iteration   2: 6.893 ops/ms
# Warmup Iteration   3: 8.507 ops/ms
Iteration   1: 8.498 ops/ms
Iteration   2: 8.544 ops/ms
Iteration   3: 8.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.586 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (8.498, 8.586, 8.716), stdev = 0.115
  CI (99.9%): [6.486, 10.686] (assumes normal distribution)


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
# Warmup Iteration   1: 8.946 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.005 ms/op
Iteration   1: 3.107 ±(99.9%) 0.009 ms/op
Iteration   2: 3.228 ±(99.9%) 0.005 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.159 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.107, 3.159, 3.228), stdev = 0.062
  CI (99.9%): [2.027, 4.291] (assumes normal distribution)


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
# Warmup Iteration   1: 6.846 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.006 ms/op
Iteration   1: 3.181 ±(99.9%) 0.006 ms/op
Iteration   2: 3.111 ±(99.9%) 0.010 ms/op
Iteration   3: 3.154 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.149 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.111, 3.149, 3.181), stdev = 0.035
  CI (99.9%): [2.506, 3.792] (assumes normal distribution)


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
# Warmup Iteration   1: 7.554 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.005 ms/op
Iteration   1: 3.253 ±(99.9%) 0.007 ms/op
Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
Iteration   3: 3.130 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.186 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.130, 3.186, 3.253), stdev = 0.062
  CI (99.9%): [2.054, 4.319] (assumes normal distribution)


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
# Warmup Iteration   1: 8.832 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.004 ms/op
Iteration   1: 3.831 ±(99.9%) 0.006 ms/op
Iteration   2: 3.800 ±(99.9%) 0.007 ms/op
Iteration   3: 3.664 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.765 ±(99.9%) 1.627 ms/op [Average]
  (min, avg, max) = (3.664, 3.765, 3.831), stdev = 0.089
  CI (99.9%): [2.138, 5.393] (assumes normal distribution)


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
# Warmup Iteration   1: 7.713 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
Iteration   1: 3.179 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 20.871 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.210 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 33.458 ms/op
                 createUser·p1.00:   33.522 ms/op

Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.140 ms/op
                 createUser·p0.999:  14.297 ms/op
                 createUser·p0.9999: 22.333 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301561
  mean =      3.180 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8995 
    [ 2.500,  5.000) = 287797 
    [ 5.000,  7.500) = 3889 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     11.674 ms/op
     p(99.9900) =     30.552 ms/op
     p(99.9990) =     33.522 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 7.177 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.166 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.696 ms/op
                 existUser·p0.999:  8.963 ms/op
                 existUser·p0.9999: 19.854 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  12.524 ms/op
                 existUser·p0.9999: 22.255 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.804 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  8.854 ms/op
                 existUser·p0.9999: 20.848 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300005
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30383 
    [ 2.500,  5.000) = 262562 
    [ 5.000,  7.500) = 6201 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     12.156 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 7.519 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.012 ms/op
Iteration   1: 3.188 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  14.846 ms/op
                 getUser·p0.9999: 20.315 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   2: 3.247 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  9.825 ms/op
                 getUser·p0.9999: 23.754 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 3.233 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  14.522 ms/op
                 getUser·p0.9999: 26.280 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297827
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11440 
    [ 2.500,  5.000) = 276836 
    [ 5.000,  7.500) = 8625 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     14.585 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     26.611 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 9.154 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.012 ms/op
Iteration   1: 3.854 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  20.087 ms/op
                 listUser·p0.9999: 26.477 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 3.903 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 21.869 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 3.820 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 18.701 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248668
  mean =      3.859 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 119 
    [ 2.500,  5.000) = 236454 
    [ 5.000,  7.500) = 9599 
    [ 7.500, 10.000) = 1818 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     24.967 ms/op
     p(99.9990) =     26.925 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.081 ± 4.623  ops/ms
ClientPb.existUser                       thrpt       3  10.396 ± 0.718  ops/ms
ClientPb.getUser                         thrpt       3   9.995 ± 7.006  ops/ms
ClientPb.listUser                        thrpt       3   8.586 ± 2.100  ops/ms
ClientPb.createUser                       avgt       3   3.159 ± 1.132   ms/op
ClientPb.existUser                        avgt       3   3.149 ± 0.643   ms/op
ClientPb.getUser                          avgt       3   3.186 ± 1.132   ms/op
ClientPb.listUser                         avgt       3   3.765 ± 1.627   ms/op
ClientPb.createUser                     sample  301561   3.180 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.674           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.552           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.522           ms/op
ClientPb.existUser                      sample  300005   3.196 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.221           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.692           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  297827   3.222 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.922           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.585           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.674           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.903           ms/op
ClientPb.listUser                       sample  248668   3.859 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.981           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.504           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.811           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.967           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
