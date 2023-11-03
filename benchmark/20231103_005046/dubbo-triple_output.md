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
# Warmup Iteration   1: 1.481 ops/ms
# Warmup Iteration   2: 3.220 ops/ms
# Warmup Iteration   3: 6.486 ops/ms
Iteration   1: 7.640 ops/ms
Iteration   2: 7.707 ops/ms
Iteration   3: 7.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.610 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (7.484, 7.610, 7.707), stdev = 0.115
  CI (99.9%): [5.520, 9.700] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.285 ops/ms
# Warmup Iteration   2: 6.827 ops/ms
# Warmup Iteration   3: 7.829 ops/ms
Iteration   1: 7.998 ops/ms
Iteration   2: 8.154 ops/ms
Iteration   3: 7.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.045 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (7.982, 8.045, 8.154), stdev = 0.095
  CI (99.9%): [6.314, 9.775] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.859 ops/ms
# Warmup Iteration   2: 6.168 ops/ms
# Warmup Iteration   3: 7.483 ops/ms
Iteration   1: 7.485 ops/ms
Iteration   2: 7.986 ops/ms
Iteration   3: 7.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.668 ±(99.9%) 5.043 ops/ms [Average]
  (min, avg, max) = (7.485, 7.668, 7.986), stdev = 0.276
  CI (99.9%): [2.625, 12.711] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.166 ops/ms
# Warmup Iteration   2: 4.870 ops/ms
# Warmup Iteration   3: 6.045 ops/ms
Iteration   1: 6.308 ops/ms
Iteration   2: 6.448 ops/ms
Iteration   3: 6.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.439 ±(99.9%) 2.310 ops/ms [Average]
  (min, avg, max) = (6.308, 6.439, 6.561), stdev = 0.127
  CI (99.9%): [4.129, 8.749] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.926 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.406 ±(99.9%) 0.004 ms/op
Iteration   1: 4.150 ±(99.9%) 0.003 ms/op
Iteration   2: 4.204 ±(99.9%) 0.003 ms/op
Iteration   3: 4.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.132 ±(99.9%) 1.508 ms/op [Average]
  (min, avg, max) = (4.042, 4.132, 4.204), stdev = 0.083
  CI (99.9%): [2.624, 5.640] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.488 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.003 ms/op
Iteration   1: 3.886 ±(99.9%) 0.002 ms/op
Iteration   2: 3.888 ±(99.9%) 0.003 ms/op
Iteration   3: 3.880 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.885 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (3.880, 3.885, 3.888), stdev = 0.004
  CI (99.9%): [3.803, 3.966] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.488 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.004 ms/op
Iteration   1: 4.100 ±(99.9%) 0.006 ms/op
Iteration   2: 4.002 ±(99.9%) 0.003 ms/op
Iteration   3: 3.985 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.029 ±(99.9%) 1.136 ms/op [Average]
  (min, avg, max) = (3.985, 4.029, 4.100), stdev = 0.062
  CI (99.9%): [2.893, 5.165] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.911 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.813 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.096 ±(99.9%) 0.006 ms/op
Iteration   1: 4.868 ±(99.9%) 0.009 ms/op
Iteration   2: 5.043 ±(99.9%) 0.007 ms/op
Iteration   3: 4.856 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.923 ±(99.9%) 1.908 ms/op [Average]
  (min, avg, max) = (4.856, 4.923, 5.043), stdev = 0.105
  CI (99.9%): [3.015, 6.831] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.331 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.085 ±(99.9%) 0.027 ms/op
Iteration   1: 4.259 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.847 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   8.202 ms/op
                 createUser·p0.999:  16.089 ms/op
                 createUser·p0.9999: 26.820 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  25.032 ms/op
                 createUser·p0.9999: 28.275 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 4.109 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.960 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   7.249 ms/op
                 createUser·p0.999:  17.622 ms/op
                 createUser·p0.9999: 31.060 ms/op
                 createUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233253
  mean =      4.111 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 198 
    [ 2.500,  5.000) = 216805 
    [ 5.000,  7.500) = 13861 
    [ 7.500, 10.000) = 1587 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.847 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     19.577 ms/op
     p(99.9900) =     30.376 ms/op
     p(99.9990) =     31.665 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.045 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.014 ms/op
Iteration   1: 3.942 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.978 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  17.333 ms/op
                 existUser·p0.9999: 26.080 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   2: 3.984 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.015 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  25.035 ms/op
                 existUser·p0.9999: 27.850 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   3: 3.903 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.963 ms/op
                 existUser·p0.999:  17.130 ms/op
                 existUser·p0.9999: 29.490 ms/op
                 existUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243397
  mean =      3.943 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 246 
    [ 2.500,  5.000) = 232396 
    [ 5.000,  7.500) = 8467 
    [ 7.500, 10.000) = 1243 
    [10.000, 12.500) = 557 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 132 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.900 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     30.302 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 12.874 ±(99.9%) 0.216 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.013 ms/op
Iteration   1: 4.142 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.421 ms/op
                 getUser·p0.99:   8.159 ms/op
                 getUser·p0.999:  23.354 ms/op
                 getUser·p0.9999: 27.574 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   2: 4.036 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  25.451 ms/op
                 getUser·p0.9999: 33.625 ms/op
                 getUser·p1.00:   34.996 ms/op

Iteration   3: 4.054 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   7.463 ms/op
                 getUser·p0.999:  13.271 ms/op
                 getUser·p0.9999: 30.347 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235459
  mean =      4.077 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 222676 
    [ 5.000,  7.500) = 9910 
    [ 7.500, 10.000) = 1823 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     23.485 ms/op
     p(99.9900) =     31.651 ms/op
     p(99.9990) =     34.557 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.658 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 6.168 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.117 ±(99.9%) 0.018 ms/op
Iteration   1: 4.913 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   8.918 ms/op
                 listUser·p0.999:  25.821 ms/op
                 listUser·p0.9999: 27.573 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   2: 4.926 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   9.066 ms/op
                 listUser·p0.999:  19.599 ms/op
                 listUser·p0.9999: 27.624 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   3: 4.901 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  17.784 ms/op
                 listUser·p0.9999: 21.735 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195316
  mean =      4.913 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 140755 
    [ 5.000,  7.500) = 49909 
    [ 7.500, 10.000) = 3441 
    [10.000, 12.500) = 449 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 117 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     28.431 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.610 ± 2.090  ops/ms
ClientPb.existUser                       thrpt       3   8.045 ± 1.731  ops/ms
ClientPb.getUser                         thrpt       3   7.668 ± 5.043  ops/ms
ClientPb.listUser                        thrpt       3   6.439 ± 2.310  ops/ms
ClientPb.createUser                       avgt       3   4.132 ± 1.508   ms/op
ClientPb.existUser                        avgt       3   3.885 ± 0.082   ms/op
ClientPb.getUser                          avgt       3   4.029 ± 1.136   ms/op
ClientPb.listUser                         avgt       3   4.923 ± 1.908   ms/op
ClientPb.createUser                     sample  233253   4.111 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.847           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.577           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.376           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.916           ms/op
ClientPb.existUser                      sample  243397   3.943 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.769           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.900           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.397           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.252           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.246           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.638           ms/op
ClientPb.getUser                        sample  235459   4.077 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.444           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.485           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.651           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.996           ms/op
ClientPb.listUser                       sample  195316   4.913 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.931           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.962           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.054           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.263           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
