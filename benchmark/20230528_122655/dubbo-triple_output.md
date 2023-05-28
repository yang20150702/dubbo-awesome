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
# Warmup Iteration   1: 2.142 ops/ms
# Warmup Iteration   2: 6.062 ops/ms
# Warmup Iteration   3: 9.095 ops/ms
Iteration   1: 9.621 ops/ms
Iteration   2: 9.587 ops/ms
Iteration   3: 9.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.657 ±(99.9%) 1.692 ops/ms [Average]
  (min, avg, max) = (9.587, 9.657, 9.762), stdev = 0.093
  CI (99.9%): [7.964, 11.349] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.028 ops/ms
# Warmup Iteration   2: 8.795 ops/ms
# Warmup Iteration   3: 9.449 ops/ms
Iteration   1: 9.568 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.770 ±(99.9%) 3.951 ops/ms [Average]
  (min, avg, max) = (9.568, 9.770, 9.998), stdev = 0.217
  CI (99.9%): [5.819, 13.720] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.829 ops/ms
# Warmup Iteration   2: 8.454 ops/ms
# Warmup Iteration   3: 9.172 ops/ms
Iteration   1: 9.290 ops/ms
Iteration   2: 9.214 ops/ms
Iteration   3: 9.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.359 ±(99.9%) 3.445 ops/ms [Average]
  (min, avg, max) = (9.214, 9.359, 9.572), stdev = 0.189
  CI (99.9%): [5.914, 12.803] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.592 ops/ms
# Warmup Iteration   2: 7.265 ops/ms
# Warmup Iteration   3: 7.783 ops/ms
Iteration   1: 8.075 ops/ms
Iteration   2: 8.193 ops/ms
Iteration   3: 7.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.055 ±(99.9%) 2.699 ops/ms [Average]
  (min, avg, max) = (7.899, 8.055, 8.193), stdev = 0.148
  CI (99.9%): [5.356, 10.754] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.765 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.006 ms/op
Iteration   1: 3.326 ±(99.9%) 0.009 ms/op
Iteration   2: 3.452 ±(99.9%) 0.005 ms/op
Iteration   3: 3.482 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.420 ±(99.9%) 1.509 ms/op [Average]
  (min, avg, max) = (3.326, 3.420, 3.482), stdev = 0.083
  CI (99.9%): [1.911, 4.929] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.985 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.003 ms/op
Iteration   1: 3.532 ±(99.9%) 0.004 ms/op
Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
Iteration   3: 3.259 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.341 ±(99.9%) 3.022 ms/op [Average]
  (min, avg, max) = (3.232, 3.341, 3.532), stdev = 0.166
  CI (99.9%): [0.319, 6.363] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.756 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.007 ms/op
Iteration   1: 3.511 ±(99.9%) 0.005 ms/op
Iteration   2: 3.306 ±(99.9%) 0.009 ms/op
Iteration   3: 3.407 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.408 ±(99.9%) 1.873 ms/op [Average]
  (min, avg, max) = (3.306, 3.408, 3.511), stdev = 0.103
  CI (99.9%): [1.536, 5.281] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.876 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.005 ms/op
Iteration   1: 3.947 ±(99.9%) 0.007 ms/op
Iteration   2: 3.817 ±(99.9%) 0.013 ms/op
Iteration   3: 3.860 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.875 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (3.817, 3.875, 3.947), stdev = 0.066
  CI (99.9%): [2.672, 5.078] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.510 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.013 ms/op
Iteration   1: 3.398 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  22.311 ms/op
                 createUser·p0.9999: 26.463 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   2: 3.321 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  19.195 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284203
  mean =      3.375 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9975 
    [ 2.500,  5.000) = 266020 
    [ 5.000,  7.500) = 7150 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     28.981 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
Iteration   1: 3.372 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  19.988 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.299 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  19.687 ms/op
                 existUser·p0.9999: 35.455 ms/op
                 existUser·p1.00:   36.045 ms/op

Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 27.693 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290554
  mean =      3.303 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11959 
    [ 2.500,  5.000) = 272214 
    [ 5.000,  7.500) = 5137 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     34.534 ms/op
     p(99.9990) =     35.920 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 9.844 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.013 ms/op
Iteration   1: 3.364 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  17.918 ms/op
                 getUser·p0.9999: 38.797 ms/op
                 getUser·p1.00:   45.416 ms/op

Iteration   2: 3.381 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.786 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   7.018 ms/op
                 getUser·p0.999:  21.199 ms/op
                 getUser·p0.9999: 27.230 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   3: 3.383 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.792 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  16.743 ms/op
                 getUser·p0.9999: 23.888 ms/op
                 getUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283960
  mean =      3.376 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 276196 
    [ 5.000, 10.000) = 7334 
    [10.000, 15.000) = 141 
    [15.000, 20.000) = 53 
    [20.000, 25.000) = 154 
    [25.000, 30.000) = 50 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     37.238 ms/op
     p(99.9990) =     40.509 ms/op
     p(99.9999) =     45.416 ms/op
    p(100.0000) =     45.416 ms/op


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
# Warmup Iteration   1: 10.749 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.015 ms/op
Iteration   1: 3.901 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.144 ms/op
                 listUser·p0.999:  15.844 ms/op
                 listUser·p0.9999: 23.940 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.040 ms/op
                 listUser·p0.999:  14.508 ms/op
                 listUser·p0.9999: 17.155 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 3.948 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 18.337 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242253
  mean =      3.960 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 234401 
    [ 5.000,  7.500) = 5745 
    [ 7.500, 10.000) = 1319 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     15.495 ms/op
     p(99.9900) =     22.661 ms/op
     p(99.9990) =     24.826 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.657 ± 1.692  ops/ms
ClientPb.existUser                       thrpt       3   9.770 ± 3.951  ops/ms
ClientPb.getUser                         thrpt       3   9.359 ± 3.445  ops/ms
ClientPb.listUser                        thrpt       3   8.055 ± 2.699  ops/ms
ClientPb.createUser                       avgt       3   3.420 ± 1.509   ms/op
ClientPb.existUser                        avgt       3   3.341 ± 3.022   ms/op
ClientPb.getUser                          avgt       3   3.408 ± 1.873   ms/op
ClientPb.listUser                         avgt       3   3.875 ± 1.203   ms/op
ClientPb.createUser                     sample  284203   3.375 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.405           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.709           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.132           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  290554   3.303 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.894           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.534           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.045           ms/op
ClientPb.getUser                        sample  283960   3.376 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.876           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.238           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.416           ms/op
ClientPb.listUser                       sample  242253   3.960 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.532           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.495           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.661           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.100           ms/op
