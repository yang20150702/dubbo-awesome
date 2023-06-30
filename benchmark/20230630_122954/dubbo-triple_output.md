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
# Warmup Iteration   1: 1.532 ops/ms
# Warmup Iteration   2: 3.202 ops/ms
# Warmup Iteration   3: 6.268 ops/ms
Iteration   1: 6.727 ops/ms
Iteration   2: 7.228 ops/ms
Iteration   3: 7.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.152 ±(99.9%) 7.150 ops/ms [Average]
  (min, avg, max) = (6.727, 7.152, 7.500), stdev = 0.392
  CI (99.9%): [0.002, 14.301] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.192 ops/ms
# Warmup Iteration   2: 6.292 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 7.722 ops/ms
Iteration   3: 7.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.769 ±(99.9%) 0.896 ops/ms [Average]
  (min, avg, max) = (7.722, 7.769, 7.820), stdev = 0.049
  CI (99.9%): [6.873, 8.665] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.113 ops/ms
# Warmup Iteration   2: 5.915 ops/ms
# Warmup Iteration   3: 7.510 ops/ms
Iteration   1: 7.327 ops/ms
Iteration   2: 7.219 ops/ms
Iteration   3: 7.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.451 ±(99.9%) 5.712 ops/ms [Average]
  (min, avg, max) = (7.219, 7.451, 7.807), stdev = 0.313
  CI (99.9%): [1.740, 13.163] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.936 ops/ms
# Warmup Iteration   2: 4.923 ops/ms
# Warmup Iteration   3: 6.154 ops/ms
Iteration   1: 6.457 ops/ms
Iteration   2: 6.344 ops/ms
Iteration   3: 6.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.426 ±(99.9%) 1.302 ops/ms [Average]
  (min, avg, max) = (6.344, 6.426, 6.476), stdev = 0.071
  CI (99.9%): [5.124, 7.727] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.248 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.437 ±(99.9%) 0.008 ms/op
Iteration   1: 4.259 ±(99.9%) 0.017 ms/op
Iteration   2: 4.364 ±(99.9%) 0.006 ms/op
Iteration   3: 4.271 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.298 ±(99.9%) 1.048 ms/op [Average]
  (min, avg, max) = (4.259, 4.298, 4.364), stdev = 0.057
  CI (99.9%): [3.250, 5.346] (assumes normal distribution)


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
# Warmup Iteration   1: 14.040 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.009 ms/op
Iteration   1: 4.004 ±(99.9%) 0.007 ms/op
Iteration   2: 4.030 ±(99.9%) 0.009 ms/op
Iteration   3: 4.287 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.107 ±(99.9%) 2.853 ms/op [Average]
  (min, avg, max) = (4.004, 4.107, 4.287), stdev = 0.156
  CI (99.9%): [1.255, 6.960] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 14.400 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.275 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.566 ±(99.9%) 0.004 ms/op
Iteration   1: 4.503 ±(99.9%) 0.007 ms/op
Iteration   2: 4.238 ±(99.9%) 0.005 ms/op
Iteration   3: 3.954 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.231 ±(99.9%) 5.013 ms/op [Average]
  (min, avg, max) = (3.954, 4.231, 4.503), stdev = 0.275
  CI (99.9%): [≈ 0, 9.244] (assumes normal distribution)


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
# Warmup Iteration   1: 15.777 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.920 ±(99.9%) 0.011 ms/op
Iteration   1: 4.853 ±(99.9%) 0.013 ms/op
Iteration   2: 5.048 ±(99.9%) 0.014 ms/op
Iteration   3: 4.705 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.869 ±(99.9%) 3.134 ms/op [Average]
  (min, avg, max) = (4.705, 4.869, 5.048), stdev = 0.172
  CI (99.9%): [1.735, 8.002] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.793 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.237 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.384 ±(99.9%) 0.019 ms/op
Iteration   1: 4.518 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.980 ms/op
                 createUser·p0.99:   10.235 ms/op
                 createUser·p0.999:  19.401 ms/op
                 createUser·p0.9999: 27.582 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   2: 3.947 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.921 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.738 ms/op
                 createUser·p0.999:  21.625 ms/op
                 createUser·p0.9999: 28.953 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 4.515 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.919 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.578 ms/op
                 createUser·p0.99:   9.028 ms/op
                 createUser·p0.999:  29.891 ms/op
                 createUser·p0.9999: 39.780 ms/op
                 createUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 222786
  mean =      4.309 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 189960 
    [ 5.000, 10.000) = 31187 
    [10.000, 15.000) = 1296 
    [15.000, 20.000) = 87 
    [20.000, 25.000) = 45 
    [25.000, 30.000) = 142 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     36.008 ms/op
     p(99.9990) =     39.896 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.072 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 4.911 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.015 ms/op
Iteration   1: 4.189 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   6.038 ms/op
                 existUser·p0.99:   8.224 ms/op
                 existUser·p0.999:  12.855 ms/op
                 existUser·p0.9999: 33.227 ms/op
                 existUser·p1.00:   34.341 ms/op

Iteration   2: 4.143 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   8.307 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 29.458 ms/op
                 existUser·p1.00:   30.507 ms/op

Iteration   3: 3.985 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.150 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  30.695 ms/op
                 existUser·p0.9999: 49.480 ms/op
                 existUser·p1.00:   52.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 233927
  mean =      4.104 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 212346 
    [ 5.000, 10.000) = 20657 
    [10.000, 15.000) = 666 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 89 
    [30.000, 35.000) = 96 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 12 
    [45.000, 50.000) = 15 
    [50.000, 55.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     42.140 ms/op
     p(99.9990) =     51.729 ms/op
     p(99.9999) =     52.036 ms/op
    p(100.0000) =     52.036 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.318 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.015 ms/op
Iteration   1: 4.626 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   7.258 ms/op
                 getUser·p0.99:   10.420 ms/op
                 getUser·p0.999:  22.509 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   2: 4.081 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  13.451 ms/op
                 getUser·p0.9999: 27.902 ms/op
                 getUser·p1.00:   32.506 ms/op

Iteration   3: 4.123 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 31.719 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 225074
  mean =      4.263 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 198041 
    [ 5.000,  7.500) = 22203 
    [ 7.500, 10.000) = 3432 
    [10.000, 12.500) = 890 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     30.556 ms/op
     p(99.9990) =     32.399 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 16.161 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.338 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.329 ±(99.9%) 0.022 ms/op
Iteration   1: 5.048 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   7.381 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  24.336 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 4.934 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.308 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  21.074 ms/op
                 listUser·p0.9999: 28.001 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   3: 4.969 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192602
  mean =      4.983 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 144947 
    [ 5.000,  7.500) = 40173 
    [ 7.500, 10.000) = 5674 
    [10.000, 12.500) = 1141 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     21.476 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     28.631 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.152 ± 7.150  ops/ms
ClientPb.existUser                       thrpt       3   7.769 ± 0.896  ops/ms
ClientPb.getUser                         thrpt       3   7.451 ± 5.712  ops/ms
ClientPb.listUser                        thrpt       3   6.426 ± 1.302  ops/ms
ClientPb.createUser                       avgt       3   4.298 ± 1.048   ms/op
ClientPb.existUser                        avgt       3   4.107 ± 2.853   ms/op
ClientPb.getUser                          avgt       3   4.231 ± 5.013   ms/op
ClientPb.listUser                         avgt       3   4.869 ± 3.134   ms/op
ClientPb.createUser                     sample  222786   4.309 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.300           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.290           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.117           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.008           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.632           ms/op
ClientPb.existUser                      sample  233927   4.104 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.204           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.110           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.906           ms/op
ClientPb.existUser:existUser·p0.9999    sample          42.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          52.036           ms/op
ClientPb.getUser                        sample  225074   4.263 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.374           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.946           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.923           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.556           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.899           ms/op
ClientPb.listUser                       sample  192602   4.983 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.318           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.912           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.476           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.903           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.934           ms/op
