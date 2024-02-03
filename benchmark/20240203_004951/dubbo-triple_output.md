# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.737 ops/ms
# Warmup Iteration   2: 11.979 ops/ms
# Warmup Iteration   3: 12.345 ops/ms
Iteration   1: 12.661 ops/ms
Iteration   2: 12.727 ops/ms
Iteration   3: 12.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.742 ±(99.9%) 1.638 ops/ms [Average]
  (min, avg, max) = (12.661, 12.742, 12.838), stdev = 0.090
  CI (99.9%): [11.104, 14.380] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.108 ops/ms
# Warmup Iteration   2: 13.131 ops/ms
# Warmup Iteration   3: 13.196 ops/ms
Iteration   1: 13.359 ops/ms
Iteration   2: 13.262 ops/ms
Iteration   3: 13.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.254 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (13.142, 13.254, 13.359), stdev = 0.109
  CI (99.9%): [11.269, 15.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.473 ops/ms
# Warmup Iteration   2: 12.566 ops/ms
# Warmup Iteration   3: 12.662 ops/ms
Iteration   1: 12.781 ops/ms
Iteration   2: 12.825 ops/ms
Iteration   3: 12.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.776 ±(99.9%) 0.947 ops/ms [Average]
  (min, avg, max) = (12.722, 12.776, 12.825), stdev = 0.052
  CI (99.9%): [11.829, 13.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.583 ops/ms
# Warmup Iteration   2: 10.455 ops/ms
# Warmup Iteration   3: 10.432 ops/ms
Iteration   1: 10.409 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.412 ±(99.9%) 0.163 ops/ms [Average]
  (min, avg, max) = (10.406, 10.412, 10.423), stdev = 0.009
  CI (99.9%): [10.250, 10.575] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
Iteration   3: 2.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.537, 2.549, 2.566), stdev = 0.015
  CI (99.9%): [2.283, 2.816] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.456, 2.473, 2.498), stdev = 0.022
  CI (99.9%): [2.071, 2.875] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.003 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.008 ms/op [Average]
  (min, avg, max) = (2.495, 2.495, 2.495), stdev = 0.001
  CI (99.9%): [2.487, 2.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.515 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
Iteration   3: 2.990 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.990, 3.005, 3.017), stdev = 0.014
  CI (99.9%): [2.755, 3.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.572 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 14.107 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  8.734 ms/op
                 createUser·p0.9999: 11.002 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374736
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 179248 
    [ 2.500,  3.750) = 191583 
    [ 3.750,  5.000) = 3185 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.837 ms/op
     p(99.9990) =     14.865 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  6.189 ms/op
                 existUser·p0.9999: 14.714 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.472 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 11.194 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385181
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 186962 
    [ 2.500,  3.750) = 195215 
    [ 3.750,  5.000) = 2291 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      6.358 ms/op
     p(99.9900) =     14.164 ms/op
     p(99.9990) =     15.067 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.771 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  10.134 ms/op
                 getUser·p0.9999: 13.913 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.447 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  6.746 ms/op
                 getUser·p0.9999: 11.637 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382789
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 188683 
    [ 2.500,  3.750) = 189037 
    [ 3.750,  5.000) = 3724 
    [ 5.000,  6.250) = 914 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      6.451 ms/op
     p(99.9900) =     13.490 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.691 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.295 ms/op
                 listUser·p1.00:   10.928 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.677 ms/op
                 listUser·p0.9999: 10.935 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.896 ms/op
                 listUser·p0.9999: 11.077 ms/op
                 listUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318729
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 92722 
    [ 2.500,  3.750) = 187307 
    [ 3.750,  5.000) = 31479 
    [ 5.000,  6.250) = 5833 
    [ 6.250,  7.500) = 667 
    [ 7.500,  8.750) = 174 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     10.961 ms/op
     p(99.9990) =     11.592 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.742 ± 1.638  ops/ms
ClientPb.existUser                       thrpt       3  13.254 ± 1.986  ops/ms
ClientPb.getUser                         thrpt       3  12.776 ± 0.947  ops/ms
ClientPb.listUser                        thrpt       3  10.412 ± 0.163  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.266   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.402   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.008   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.250   ms/op
ClientPb.createUser                     sample  374736   2.558 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.782           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.837           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.514           ms/op
ClientPb.existUser                      sample  385181   2.490 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.779           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.358           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.164           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.548           ms/op
ClientPb.getUser                        sample  382789   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.451           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.490           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.696           ms/op
ClientPb.listUser                       sample  318729   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.961           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.813           ms/op
