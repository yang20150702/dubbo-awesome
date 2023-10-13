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
# Warmup Iteration   1: 1.553 ops/ms
# Warmup Iteration   2: 3.189 ops/ms
# Warmup Iteration   3: 6.474 ops/ms
Iteration   1: 7.136 ops/ms
Iteration   2: 7.070 ops/ms
Iteration   3: 7.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.169 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (7.070, 7.169, 7.300), stdev = 0.119
  CI (99.9%): [5.004, 9.333] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 6.285 ops/ms
# Warmup Iteration   3: 7.485 ops/ms
Iteration   1: 7.862 ops/ms
Iteration   2: 7.750 ops/ms
Iteration   3: 7.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.820 ±(99.9%) 1.103 ops/ms [Average]
  (min, avg, max) = (7.750, 7.820, 7.862), stdev = 0.060
  CI (99.9%): [6.717, 8.923] (assumes normal distribution)


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
# Warmup Iteration   1: 1.975 ops/ms
# Warmup Iteration   2: 6.125 ops/ms
# Warmup Iteration   3: 7.501 ops/ms
Iteration   1: 7.754 ops/ms
Iteration   2: 7.647 ops/ms
Iteration   3: 7.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.671 ±(99.9%) 1.349 ops/ms [Average]
  (min, avg, max) = (7.613, 7.671, 7.754), stdev = 0.074
  CI (99.9%): [6.322, 9.020] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.002 ops/ms
# Warmup Iteration   2: 5.224 ops/ms
# Warmup Iteration   3: 5.960 ops/ms
Iteration   1: 6.238 ops/ms
Iteration   2: 6.371 ops/ms
Iteration   3: 6.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.507 ±(99.9%) 6.504 ops/ms [Average]
  (min, avg, max) = (6.238, 6.507, 6.911), stdev = 0.357
  CI (99.9%): [0.003, 13.011] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.128 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.629 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.459 ±(99.9%) 0.005 ms/op
Iteration   1: 4.205 ±(99.9%) 0.004 ms/op
Iteration   2: 3.986 ±(99.9%) 0.004 ms/op
Iteration   3: 4.119 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.103 ±(99.9%) 2.019 ms/op [Average]
  (min, avg, max) = (3.986, 4.103, 4.205), stdev = 0.111
  CI (99.9%): [2.084, 6.123] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.371 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.064 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.005 ms/op
Iteration   1: 4.069 ±(99.9%) 0.005 ms/op
Iteration   2: 3.895 ±(99.9%) 0.008 ms/op
Iteration   3: 3.861 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.942 ±(99.9%) 2.035 ms/op [Average]
  (min, avg, max) = (3.861, 3.942, 4.069), stdev = 0.112
  CI (99.9%): [1.907, 5.977] (assumes normal distribution)


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
# Warmup Iteration   1: 13.202 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.778 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.004 ms/op
Iteration   1: 4.255 ±(99.9%) 0.003 ms/op
Iteration   2: 3.979 ±(99.9%) 0.007 ms/op
Iteration   3: 3.917 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.050 ±(99.9%) 3.278 ms/op [Average]
  (min, avg, max) = (3.917, 4.050, 4.255), stdev = 0.180
  CI (99.9%): [0.772, 7.328] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.700 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.025 ±(99.9%) 0.006 ms/op
Iteration   1: 4.950 ±(99.9%) 0.006 ms/op
Iteration   2: 4.916 ±(99.9%) 0.010 ms/op
Iteration   3: 4.613 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.826 ±(99.9%) 3.392 ms/op [Average]
  (min, avg, max) = (4.613, 4.826, 4.950), stdev = 0.186
  CI (99.9%): [1.435, 8.218] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.292 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.534 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.937 ±(99.9%) 0.024 ms/op
Iteration   1: 4.441 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.944 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.914 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  17.269 ms/op
                 createUser·p0.9999: 29.732 ms/op
                 createUser·p1.00:   30.933 ms/op

Iteration   2: 4.266 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   8.266 ms/op
                 createUser·p0.999:  25.363 ms/op
                 createUser·p0.9999: 31.605 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 4.253 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.114 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.071 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  20.954 ms/op
                 createUser·p0.9999: 34.537 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 222240
  mean =      4.318 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 207 
    [ 2.500,  5.000) = 193970 
    [ 5.000,  7.500) = 23083 
    [ 7.500, 10.000) = 3542 
    [10.000, 12.500) = 812 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     24.240 ms/op
     p(99.9900) =     33.736 ms/op
     p(99.9990) =     34.836 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 12.752 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.012 ms/op
Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  20.497 ms/op
                 existUser·p0.9999: 27.750 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   2: 3.957 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   8.700 ms/op
                 existUser·p0.999:  15.847 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 4.049 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.911 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   8.061 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 29.173 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241253
  mean =      3.976 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 361 
    [ 2.500,  5.000) = 226193 
    [ 5.000,  7.500) = 11455 
    [ 7.500, 10.000) = 2438 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.776 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.958 ms/op
     p(99.9000) =     16.982 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     30.125 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 15.021 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.986 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.013 ms/op
Iteration   1: 4.169 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  21.243 ms/op
                 getUser·p0.9999: 25.766 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.905 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  11.897 ms/op
                 getUser·p0.9999: 25.157 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 4.129 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.404 ms/op
                 getUser·p0.999:  24.412 ms/op
                 getUser·p0.9999: 27.140 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236020
  mean =      4.064 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 222815 
    [ 5.000,  7.500) = 9666 
    [ 7.500, 10.000) = 2604 
    [10.000, 12.500) = 457 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 14.917 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.547 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.977 ±(99.9%) 0.016 ms/op
Iteration   1: 4.810 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.216 ms/op
                 listUser·p0.999:  23.016 ms/op
                 listUser·p0.9999: 25.363 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.831 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  18.798 ms/op
                 listUser·p0.9999: 20.212 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 4.947 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197389
  mean =      4.862 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 147666 
    [ 5.000,  7.500) = 45639 
    [ 7.500, 10.000) = 2885 
    [10.000, 12.500) = 509 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     24.536 ms/op
     p(99.9990) =     26.300 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.169 ± 2.164  ops/ms
ClientPb.existUser                       thrpt       3   7.820 ± 1.103  ops/ms
ClientPb.getUser                         thrpt       3   7.671 ± 1.349  ops/ms
ClientPb.listUser                        thrpt       3   6.507 ± 6.504  ops/ms
ClientPb.createUser                       avgt       3   4.103 ± 2.019   ms/op
ClientPb.existUser                        avgt       3   3.942 ± 2.035   ms/op
ClientPb.getUser                          avgt       3   4.050 ± 3.278   ms/op
ClientPb.listUser                         avgt       3   4.826 ± 3.392   ms/op
ClientPb.createUser                     sample  222240   4.318 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.690           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.243           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.324           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.011           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.240           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.736           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  241253   3.976 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.776           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.958           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.982           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.853           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  236020   4.064 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.665           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.946           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.266           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.608           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.967           ms/op
ClientPb.listUser                       sample  197389   4.862 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.739           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.678           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.536           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
