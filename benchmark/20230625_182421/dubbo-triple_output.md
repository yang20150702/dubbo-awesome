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
# Warmup Iteration   1: 1.765 ops/ms
# Warmup Iteration   2: 4.545 ops/ms
# Warmup Iteration   3: 7.692 ops/ms
Iteration   1: 8.231 ops/ms
Iteration   2: 9.047 ops/ms
Iteration   3: 9.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.793 ±(99.9%) 8.895 ops/ms [Average]
  (min, avg, max) = (8.231, 8.793, 9.102), stdev = 0.488
  CI (99.9%): [≈ 0, 17.689] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.323 ops/ms
# Warmup Iteration   2: 7.979 ops/ms
# Warmup Iteration   3: 9.141 ops/ms
Iteration   1: 9.500 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 9.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.296 ±(99.9%) 3.217 ops/ms [Average]
  (min, avg, max) = (9.193, 9.296, 9.500), stdev = 0.176
  CI (99.9%): [6.080, 12.513] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.751 ops/ms
# Warmup Iteration   2: 8.035 ops/ms
# Warmup Iteration   3: 8.438 ops/ms
Iteration   1: 9.253 ops/ms
Iteration   2: 9.227 ops/ms
Iteration   3: 9.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.286 ±(99.9%) 1.463 ops/ms [Average]
  (min, avg, max) = (9.227, 9.286, 9.377), stdev = 0.080
  CI (99.9%): [7.823, 10.749] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.387 ops/ms
# Warmup Iteration   2: 6.965 ops/ms
# Warmup Iteration   3: 7.487 ops/ms
Iteration   1: 7.613 ops/ms
Iteration   2: 7.943 ops/ms
Iteration   3: 7.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.737 ±(99.9%) 3.285 ops/ms [Average]
  (min, avg, max) = (7.613, 7.737, 7.943), stdev = 0.180
  CI (99.9%): [4.452, 11.022] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.913 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.004 ms/op
Iteration   1: 3.691 ±(99.9%) 0.007 ms/op
Iteration   2: 3.690 ±(99.9%) 0.004 ms/op
Iteration   3: 3.450 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.610 ±(99.9%) 2.531 ms/op [Average]
  (min, avg, max) = (3.450, 3.610, 3.691), stdev = 0.139
  CI (99.9%): [1.079, 6.141] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.796 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.007 ms/op
Iteration   1: 3.367 ±(99.9%) 0.007 ms/op
Iteration   2: 3.488 ±(99.9%) 0.004 ms/op
Iteration   3: 3.395 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.417 ±(99.9%) 1.155 ms/op [Average]
  (min, avg, max) = (3.367, 3.417, 3.488), stdev = 0.063
  CI (99.9%): [2.262, 4.571] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.744 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.004 ms/op
Iteration   1: 3.621 ±(99.9%) 0.005 ms/op
Iteration   2: 3.472 ±(99.9%) 0.007 ms/op
Iteration   3: 3.517 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.537 ±(99.9%) 1.389 ms/op [Average]
  (min, avg, max) = (3.472, 3.537, 3.621), stdev = 0.076
  CI (99.9%): [2.148, 4.926] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 12.852 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.011 ms/op
Iteration   1: 4.195 ±(99.9%) 0.005 ms/op
Iteration   2: 4.020 ±(99.9%) 0.013 ms/op
Iteration   3: 4.177 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.131 ±(99.9%) 1.754 ms/op [Average]
  (min, avg, max) = (4.020, 4.131, 4.195), stdev = 0.096
  CI (99.9%): [2.377, 5.884] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.392 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.015 ms/op
Iteration   1: 3.644 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  18.724 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 3.523 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  19.628 ms/op
                 createUser·p0.9999: 24.737 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   3: 3.510 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  21.950 ms/op
                 createUser·p0.9999: 25.567 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269969
  mean =      3.558 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4295 
    [ 2.500,  5.000) = 257681 
    [ 5.000,  7.500) = 6433 
    [ 7.500, 10.000) = 961 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     19.827 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     26.097 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.237 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.009 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  20.040 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  14.353 ms/op
                 existUser·p0.9999: 26.660 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   3: 3.379 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  24.869 ms/op
                 existUser·p0.9999: 29.824 ms/op
                 existUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282621
  mean =      3.393 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8126 
    [ 2.500,  5.000) = 269217 
    [ 5.000,  7.500) = 4246 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     28.039 ms/op
     p(99.9990) =     30.573 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.239 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.013 ms/op
Iteration   1: 3.708 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.971 ms/op
                 getUser·p0.999:  23.254 ms/op
                 getUser·p0.9999: 29.765 ms/op
                 getUser·p1.00:   32.178 ms/op

Iteration   2: 3.518 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  10.754 ms/op
                 getUser·p0.9999: 26.470 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.567 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.751 ms/op
                 getUser·p0.999:  26.280 ms/op
                 getUser·p0.9999: 40.108 ms/op
                 getUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267076
  mean =      3.596 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 256414 
    [ 5.000, 10.000) = 9996 
    [10.000, 15.000) = 383 
    [15.000, 20.000) = 22 
    [20.000, 25.000) = 73 
    [25.000, 30.000) = 122 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 49 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     19.265 ms/op
     p(99.9900) =     38.011 ms/op
     p(99.9990) =     40.654 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.136 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.871 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.015 ms/op
Iteration   1: 4.265 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  22.992 ms/op
                 listUser·p0.9999: 25.575 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 4.197 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.098 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  17.688 ms/op
                 listUser·p0.9999: 18.723 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 4.264 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 21.577 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226486
  mean =      4.242 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 210017 
    [ 5.000,  7.500) = 13208 
    [ 7.500, 10.000) = 2010 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.289 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     25.918 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.793 ± 8.895  ops/ms
ClientPb.existUser                       thrpt       3   9.296 ± 3.217  ops/ms
ClientPb.getUser                         thrpt       3   9.286 ± 1.463  ops/ms
ClientPb.listUser                        thrpt       3   7.737 ± 3.285  ops/ms
ClientPb.createUser                       avgt       3   3.610 ± 2.531   ms/op
ClientPb.existUser                        avgt       3   3.417 ± 1.155   ms/op
ClientPb.getUser                          avgt       3   3.537 ± 1.389   ms/op
ClientPb.listUser                         avgt       3   4.131 ± 1.754   ms/op
ClientPb.createUser                     sample  269969   3.558 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.827           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.805           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.066           ms/op
ClientPb.existUser                      sample  282621   3.393 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.448           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.931           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.385           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.039           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.359           ms/op
ClientPb.getUser                        sample  267076   3.596 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.714           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.225           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.265           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.011           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.698           ms/op
ClientPb.listUser                       sample  226486   4.242 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.289           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.290           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.022           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.936           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
