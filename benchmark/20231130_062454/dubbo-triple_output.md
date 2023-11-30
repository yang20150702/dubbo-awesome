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
# Warmup Iteration   1: 4.854 ops/ms
# Warmup Iteration   2: 12.222 ops/ms
# Warmup Iteration   3: 12.470 ops/ms
Iteration   1: 12.767 ops/ms
Iteration   2: 12.647 ops/ms
Iteration   3: 12.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.704 ±(99.9%) 1.095 ops/ms [Average]
  (min, avg, max) = (12.647, 12.704, 12.767), stdev = 0.060
  CI (99.9%): [11.609, 13.799] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.922 ops/ms
# Warmup Iteration   2: 13.171 ops/ms
# Warmup Iteration   3: 13.273 ops/ms
Iteration   1: 13.081 ops/ms
Iteration   2: 13.349 ops/ms
Iteration   3: 13.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.190 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (13.081, 13.190, 13.349), stdev = 0.141
  CI (99.9%): [10.621, 15.759] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.848 ops/ms
# Warmup Iteration   2: 12.595 ops/ms
# Warmup Iteration   3: 12.820 ops/ms
Iteration   1: 12.680 ops/ms
Iteration   2: 12.930 ops/ms
Iteration   3: 12.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.820 ±(99.9%) 2.329 ops/ms [Average]
  (min, avg, max) = (12.680, 12.820, 12.930), stdev = 0.128
  CI (99.9%): [10.492, 15.149] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.506 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.712 ops/ms
Iteration   2: 10.665 ops/ms
Iteration   3: 10.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.663 ±(99.9%) 0.907 ops/ms [Average]
  (min, avg, max) = (10.612, 10.663, 10.712), stdev = 0.050
  CI (99.9%): [9.756, 11.570] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.003 ms/op
Iteration   3: 2.576 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (2.499, 2.532, 2.576), stdev = 0.040
  CI (99.9%): [1.810, 3.254] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.444, 2.454, 2.460), stdev = 0.009
  CI (99.9%): [2.295, 2.613] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.447 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (2.433, 2.447, 2.457), stdev = 0.013
  CI (99.9%): [2.215, 2.679] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.702 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.005 ms/op
Iteration   1: 2.934 ±(99.9%) 0.006 ms/op
Iteration   2: 2.926 ±(99.9%) 0.005 ms/op
Iteration   3: 2.935 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.932 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (2.926, 2.932, 2.935), stdev = 0.005
  CI (99.9%): [2.843, 3.020] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  11.529 ms/op
                 createUser·p0.9999: 14.230 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  6.570 ms/op
                 createUser·p0.9999: 12.780 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 10.715 ms/op
                 createUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384859
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 186855 
    [ 2.500,  3.750) = 194182 
    [ 3.750,  5.000) = 2928 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.555 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     14.874 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  5.336 ms/op
                 existUser·p0.9999: 13.940 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.405 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  7.496 ms/op
                 existUser·p0.9999: 14.004 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  7.806 ms/op
                 existUser·p0.9999: 11.055 ms/op
                 existUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397223
  mean =      2.414 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 200973 
    [ 2.500,  3.750) = 192674 
    [ 3.750,  5.000) = 2741 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      7.433 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.483 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  10.684 ms/op
                 getUser·p0.9999: 13.113 ms/op
                 getUser·p1.00:   13.533 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  5.885 ms/op
                 getUser·p0.9999: 14.075 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.797 ms/op
                 getUser·p0.9999: 12.195 ms/op
                 getUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384569
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 190746 
    [ 2.500,  3.750) = 189184 
    [ 3.750,  5.000) = 3319 
    [ 5.000,  6.250) = 772 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.578 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
Iteration   1: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.284 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.433 ms/op
                 listUser·p0.9999: 11.633 ms/op
                 listUser·p1.00:   13.894 ms/op

Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.502 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321731
  mean =      2.981 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 94845 
    [ 2.500,  3.750) = 190693 
    [ 3.750,  5.000) = 29662 
    [ 5.000,  6.250) = 5321 
    [ 6.250,  7.500) = 413 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 304 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.187 ms/op
     p(99.9990) =     12.255 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.704 ± 1.095  ops/ms
ClientPb.existUser                       thrpt       3  13.190 ± 2.569  ops/ms
ClientPb.getUser                         thrpt       3  12.820 ± 2.329  ops/ms
ClientPb.listUser                        thrpt       3  10.663 ± 0.907  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.722   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.159   ms/op
ClientPb.getUser                          avgt       3   2.447 ± 0.232   ms/op
ClientPb.listUser                         avgt       3   2.932 ± 0.088   ms/op
ClientPb.createUser                     sample  384859   2.492 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.721           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.555           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.631           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.106           ms/op
ClientPb.existUser                      sample  397223   2.414 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.971           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.433           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.779           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.221           ms/op
ClientPb.getUser                        sample  384569   2.494 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.828           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.765           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.238           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.959           ms/op
ClientPb.listUser                       sample  321731   2.981 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.779           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.187           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.894           ms/op
