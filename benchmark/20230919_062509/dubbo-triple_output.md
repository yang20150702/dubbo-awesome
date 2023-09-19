# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.587 ops/ms
# Warmup Iteration   2: 3.172 ops/ms
# Warmup Iteration   3: 6.869 ops/ms
Iteration   1: 7.404 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 7.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.738 ±(99.9%) 5.315 ops/ms [Average]
  (min, avg, max) = (7.404, 7.738, 7.941), stdev = 0.291
  CI (99.9%): [2.423, 13.053] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.372 ops/ms
# Warmup Iteration   2: 7.403 ops/ms
# Warmup Iteration   3: 8.060 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.416 ops/ms
Iteration   3: 8.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.244 ±(99.9%) 2.800 ops/ms [Average]
  (min, avg, max) = (8.121, 8.244, 8.416), stdev = 0.154
  CI (99.9%): [5.444, 11.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.027 ops/ms
# Warmup Iteration   2: 6.374 ops/ms
# Warmup Iteration   3: 7.591 ops/ms
Iteration   1: 7.921 ops/ms
Iteration   2: 7.662 ops/ms
Iteration   3: 7.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.782 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (7.662, 7.782, 7.921), stdev = 0.131
  CI (99.9%): [5.399, 10.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.122 ops/ms
# Warmup Iteration   2: 5.641 ops/ms
# Warmup Iteration   3: 6.681 ops/ms
Iteration   1: 6.602 ops/ms
Iteration   2: 6.694 ops/ms
Iteration   3: 7.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.776 ±(99.9%) 4.115 ops/ms [Average]
  (min, avg, max) = (6.602, 6.776, 7.031), stdev = 0.226
  CI (99.9%): [2.661, 10.891] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.571 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.822 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.371 ±(99.9%) 0.004 ms/op
Iteration   1: 4.330 ±(99.9%) 0.005 ms/op
Iteration   2: 4.117 ±(99.9%) 0.006 ms/op
Iteration   3: 4.206 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.218 ±(99.9%) 1.958 ms/op [Average]
  (min, avg, max) = (4.117, 4.218, 4.330), stdev = 0.107
  CI (99.9%): [2.260, 6.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.015 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.006 ms/op
Iteration   1: 3.898 ±(99.9%) 0.007 ms/op
Iteration   2: 3.872 ±(99.9%) 0.005 ms/op
Iteration   3: 3.972 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.914 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (3.872, 3.914, 3.972), stdev = 0.052
  CI (99.9%): [2.964, 4.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.696 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.876 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.003 ms/op
Iteration   1: 4.205 ±(99.9%) 0.004 ms/op
Iteration   2: 4.286 ±(99.9%) 0.005 ms/op
Iteration   3: 4.007 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.166 ±(99.9%) 2.613 ms/op [Average]
  (min, avg, max) = (4.007, 4.166, 4.286), stdev = 0.143
  CI (99.9%): [1.553, 6.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.356 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.588 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.909 ±(99.9%) 0.007 ms/op
Iteration   1: 4.830 ±(99.9%) 0.010 ms/op
Iteration   2: 4.734 ±(99.9%) 0.006 ms/op
Iteration   3: 4.771 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.779 ±(99.9%) 0.881 ms/op [Average]
  (min, avg, max) = (4.734, 4.779, 4.830), stdev = 0.048
  CI (99.9%): [3.898, 5.659] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.430 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.810 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.451 ±(99.9%) 0.018 ms/op
Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  23.847 ms/op
                 createUser·p0.9999: 26.121 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 4.079 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  18.478 ms/op
                 createUser·p0.9999: 27.727 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 4.049 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  28.669 ms/op
                 createUser·p0.9999: 32.512 ms/op
                 createUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236700
  mean =      4.059 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 462 
    [ 2.500,  5.000) = 221711 
    [ 5.000,  7.500) = 12503 
    [ 7.500, 10.000) = 1353 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     23.888 ms/op
     p(99.9900) =     31.326 ms/op
     p(99.9990) =     32.744 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.178 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.013 ms/op
Iteration   1: 4.019 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   7.242 ms/op
                 existUser·p0.999:  16.660 ms/op
                 existUser·p0.9999: 24.939 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 3.919 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.884 ms/op
                 existUser·p0.999:  24.292 ms/op
                 existUser·p0.9999: 27.323 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.966 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.889 ms/op
                 existUser·p0.999:  15.630 ms/op
                 existUser·p0.9999: 28.803 ms/op
                 existUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241863
  mean =      3.968 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 297 
    [ 2.500,  5.000) = 230252 
    [ 5.000,  7.500) = 9547 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     16.733 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     29.581 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.845 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.014 ms/op
Iteration   1: 4.264 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   9.191 ms/op
                 getUser·p0.999:  23.820 ms/op
                 getUser·p0.9999: 26.869 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 4.030 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  13.789 ms/op
                 getUser·p0.9999: 28.213 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   3: 4.014 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  28.089 ms/op
                 getUser·p0.9999: 31.426 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234365
  mean =      4.100 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 221662 
    [ 5.000,  7.500) = 10076 
    [ 7.500, 10.000) = 1643 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.670 ms/op
     p(99.9000) =     23.843 ms/op
     p(99.9900) =     30.642 ms/op
     p(99.9990) =     32.172 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.364 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.856 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.063 ±(99.9%) 0.019 ms/op
Iteration   1: 4.800 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  25.210 ms/op
                 listUser·p0.9999: 27.886 ms/op
                 listUser·p1.00:   28.410 ms/op

Iteration   2: 4.763 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 26.537 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   3: 4.793 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.621 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  17.180 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200538
  mean =      4.785 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 163354 
    [ 5.000,  7.500) = 33020 
    [ 7.500, 10.000) = 2913 
    [10.000, 12.500) = 693 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     27.161 ms/op
     p(99.9990) =     28.245 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.738 ± 5.315  ops/ms
ClientPb.existUser                       thrpt       3   8.244 ± 2.800  ops/ms
ClientPb.getUser                         thrpt       3   7.782 ± 2.383  ops/ms
ClientPb.listUser                        thrpt       3   6.776 ± 4.115  ops/ms
ClientPb.createUser                       avgt       3   4.218 ± 1.958   ms/op
ClientPb.existUser                        avgt       3   3.914 ± 0.950   ms/op
ClientPb.getUser                          avgt       3   4.166 ± 2.613   ms/op
ClientPb.listUser                         avgt       3   4.779 ± 0.881   ms/op
ClientPb.createUser                     sample  236700   4.059 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.569           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.888           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.326           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.866           ms/op
ClientPb.existUser                      sample  241863   3.968 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.040           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.448           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.045           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.733           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.951           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.048           ms/op
ClientPb.getUser                        sample  234365   4.100 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.137           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.670           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.642           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.670           ms/op
ClientPb.listUser                       sample  200538   4.785 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.226           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.447           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.161           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.410           ms/op
