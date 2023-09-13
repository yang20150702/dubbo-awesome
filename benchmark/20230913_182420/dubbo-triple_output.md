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
# Warmup Iteration   1: 1.599 ops/ms
# Warmup Iteration   2: 3.698 ops/ms
# Warmup Iteration   3: 7.269 ops/ms
Iteration   1: 7.755 ops/ms
Iteration   2: 7.911 ops/ms
Iteration   3: 8.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.890 ±(99.9%) 2.293 ops/ms [Average]
  (min, avg, max) = (7.755, 7.890, 8.004), stdev = 0.126
  CI (99.9%): [5.597, 10.183] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.354 ops/ms
# Warmup Iteration   2: 6.381 ops/ms
# Warmup Iteration   3: 8.214 ops/ms
Iteration   1: 8.474 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 8.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.258 ±(99.9%) 3.442 ops/ms [Average]
  (min, avg, max) = (8.130, 8.258, 8.474), stdev = 0.189
  CI (99.9%): [4.816, 11.699] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.390 ops/ms
# Warmup Iteration   2: 6.479 ops/ms
# Warmup Iteration   3: 8.021 ops/ms
Iteration   1: 8.030 ops/ms
Iteration   2: 8.056 ops/ms
Iteration   3: 7.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.945 ±(99.9%) 3.104 ops/ms [Average]
  (min, avg, max) = (7.749, 7.945, 8.056), stdev = 0.170
  CI (99.9%): [4.841, 11.049] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 6.099 ops/ms
# Warmup Iteration   3: 6.570 ops/ms
Iteration   1: 6.527 ops/ms
Iteration   2: 6.667 ops/ms
Iteration   3: 6.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.649 ±(99.9%) 2.080 ops/ms [Average]
  (min, avg, max) = (6.527, 6.649, 6.752), stdev = 0.114
  CI (99.9%): [4.569, 8.729] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.429 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.004 ms/op
Iteration   1: 4.176 ±(99.9%) 0.005 ms/op
Iteration   2: 4.040 ±(99.9%) 0.004 ms/op
Iteration   3: 3.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.063 ±(99.9%) 1.891 ms/op [Average]
  (min, avg, max) = (3.973, 4.063, 4.176), stdev = 0.104
  CI (99.9%): [2.172, 5.954] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.125 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.005 ms/op
Iteration   1: 3.846 ±(99.9%) 0.005 ms/op
Iteration   2: 3.868 ±(99.9%) 0.006 ms/op
Iteration   3: 3.935 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.883 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.846, 3.883, 3.935), stdev = 0.046
  CI (99.9%): [3.036, 4.731] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.994 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.004 ms/op
Iteration   1: 4.088 ±(99.9%) 0.005 ms/op
Iteration   2: 4.057 ±(99.9%) 0.005 ms/op
Iteration   3: 4.080 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.075 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (4.057, 4.075, 4.088), stdev = 0.016
  CI (99.9%): [3.783, 4.367] (assumes normal distribution)


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
# Warmup Iteration   1: 14.512 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.608 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.036 ±(99.9%) 0.005 ms/op
Iteration   1: 4.827 ±(99.9%) 0.005 ms/op
Iteration   2: 4.803 ±(99.9%) 0.007 ms/op
Iteration   3: 4.755 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.795 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (4.755, 4.795, 4.827), stdev = 0.037
  CI (99.9%): [4.125, 5.464] (assumes normal distribution)


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
# Warmup Iteration   1: 12.687 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.860 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.549 ±(99.9%) 0.017 ms/op
Iteration   1: 4.063 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.481 ms/op
                 createUser·p0.999:  12.035 ms/op
                 createUser·p0.9999: 24.359 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   2: 3.971 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  22.494 ms/op
                 createUser·p0.9999: 25.164 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.907 ms/op
                 createUser·p0.999:  19.038 ms/op
                 createUser·p0.9999: 30.376 ms/op
                 createUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238903
  mean =      4.016 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 526 
    [ 2.500,  5.000) = 226241 
    [ 5.000,  7.500) = 10644 
    [ 7.500, 10.000) = 903 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     19.177 ms/op
     p(99.9900) =     29.600 ms/op
     p(99.9990) =     31.124 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.313 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.011 ms/op
Iteration   1: 3.811 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  11.043 ms/op
                 existUser·p0.9999: 23.875 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.869 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  15.654 ms/op
                 existUser·p0.9999: 25.656 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 4.054 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   8.094 ms/op
                 existUser·p0.999:  24.150 ms/op
                 existUser·p0.9999: 28.508 ms/op
                 existUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245581
  mean =      3.909 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 301 
    [ 2.500,  5.000) = 233081 
    [ 5.000,  7.500) = 9849 
    [ 7.500, 10.000) = 1681 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.440 ms/op
     p(99.9000) =     16.634 ms/op
     p(99.9900) =     27.798 ms/op
     p(99.9990) =     29.050 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 12.347 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.712 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.015 ms/op
Iteration   1: 4.123 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   8.376 ms/op
                 getUser·p0.999:  23.975 ms/op
                 getUser·p0.9999: 26.182 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   2: 4.152 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.956 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.005 ms/op
                 getUser·p0.999:  14.320 ms/op
                 getUser·p0.9999: 27.558 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   3: 4.105 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  27.200 ms/op
                 getUser·p0.9999: 34.027 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232562
  mean =      4.126 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 220390 
    [ 5.000,  7.500) = 9766 
    [ 7.500, 10.000) = 1528 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     33.022 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 14.152 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.330 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.000 ±(99.9%) 0.016 ms/op
Iteration   1: 4.875 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  24.915 ms/op
                 listUser·p0.9999: 29.305 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   2: 4.948 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   9.025 ms/op
                 listUser·p0.999:  18.801 ms/op
                 listUser·p0.9999: 22.434 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 4.826 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  17.030 ms/op
                 listUser·p0.9999: 19.775 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196534
  mean =      4.882 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 142577 
    [ 5.000,  7.500) = 49773 
    [ 7.500, 10.000) = 2941 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     19.477 ms/op
     p(99.9900) =     27.635 ms/op
     p(99.9990) =     30.362 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.890 ± 2.293  ops/ms
ClientPb.existUser                       thrpt       3   8.258 ± 3.442  ops/ms
ClientPb.getUser                         thrpt       3   7.945 ± 3.104  ops/ms
ClientPb.listUser                        thrpt       3   6.649 ± 2.080  ops/ms
ClientPb.createUser                       avgt       3   4.063 ± 1.891   ms/op
ClientPb.existUser                        avgt       3   3.883 ± 0.847   ms/op
ClientPb.getUser                          avgt       3   4.075 ± 0.292   ms/op
ClientPb.listUser                         avgt       3   4.795 ± 0.670   ms/op
ClientPb.createUser                     sample  238903   4.016 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.266           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.177           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.600           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.162           ms/op
ClientPb.existUser                      sample  245581   3.909 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.440           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.634           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.798           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.786           ms/op
ClientPb.getUser                        sample  232562   4.126 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.346           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.520           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.314           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.022           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  196534   4.882 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.454           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.390           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.929           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.477           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.635           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.900           ms/op
