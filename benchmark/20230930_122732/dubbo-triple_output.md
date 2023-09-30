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
# Warmup Iteration   1: 1.574 ops/ms
# Warmup Iteration   2: 3.506 ops/ms
# Warmup Iteration   3: 6.919 ops/ms
Iteration   1: 7.199 ops/ms
Iteration   2: 7.511 ops/ms
Iteration   3: 7.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.492 ±(99.9%) 5.167 ops/ms [Average]
  (min, avg, max) = (7.199, 7.492, 7.765), stdev = 0.283
  CI (99.9%): [2.324, 12.659] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.262 ops/ms
# Warmup Iteration   2: 6.953 ops/ms
# Warmup Iteration   3: 7.668 ops/ms
Iteration   1: 7.768 ops/ms
Iteration   2: 8.309 ops/ms
Iteration   3: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.080 ±(99.9%) 5.107 ops/ms [Average]
  (min, avg, max) = (7.768, 8.080, 8.309), stdev = 0.280
  CI (99.9%): [2.973, 13.188] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.105 ops/ms
# Warmup Iteration   2: 5.938 ops/ms
# Warmup Iteration   3: 7.802 ops/ms
Iteration   1: 7.519 ops/ms
Iteration   2: 7.773 ops/ms
Iteration   3: 7.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.669 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (7.519, 7.669, 7.773), stdev = 0.133
  CI (99.9%): [5.244, 10.095] (assumes normal distribution)


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
# Warmup Iteration   1: 1.912 ops/ms
# Warmup Iteration   2: 5.025 ops/ms
# Warmup Iteration   3: 6.140 ops/ms
Iteration   1: 6.594 ops/ms
Iteration   2: 6.221 ops/ms
Iteration   3: 6.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.411 ±(99.9%) 3.407 ops/ms [Average]
  (min, avg, max) = (6.221, 6.411, 6.594), stdev = 0.187
  CI (99.9%): [3.004, 9.818] (assumes normal distribution)


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
# Warmup Iteration   1: 13.208 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.441 ±(99.9%) 0.008 ms/op
Iteration   1: 4.295 ±(99.9%) 0.004 ms/op
Iteration   2: 4.077 ±(99.9%) 0.009 ms/op
Iteration   3: 4.276 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.216 ±(99.9%) 2.200 ms/op [Average]
  (min, avg, max) = (4.077, 4.216, 4.295), stdev = 0.121
  CI (99.9%): [2.016, 6.416] (assumes normal distribution)


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
# Warmup Iteration   1: 13.147 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.796 ±(99.9%) 0.005 ms/op
Iteration   2: 3.884 ±(99.9%) 0.003 ms/op
Iteration   3: 4.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.898 ±(99.9%) 1.995 ms/op [Average]
  (min, avg, max) = (3.796, 3.898, 4.014), stdev = 0.109
  CI (99.9%): [1.904, 5.893] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.007 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.005 ms/op
Iteration   1: 4.195 ±(99.9%) 0.005 ms/op
Iteration   2: 4.104 ±(99.9%) 0.005 ms/op
Iteration   3: 4.070 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.123 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (4.070, 4.123, 4.195), stdev = 0.065
  CI (99.9%): [2.939, 5.307] (assumes normal distribution)


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
# Warmup Iteration   1: 14.626 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.153 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.154 ±(99.9%) 0.008 ms/op
Iteration   1: 4.956 ±(99.9%) 0.006 ms/op
Iteration   2: 5.032 ±(99.9%) 0.009 ms/op
Iteration   3: 4.799 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.929 ±(99.9%) 2.167 ms/op [Average]
  (min, avg, max) = (4.799, 4.929, 5.032), stdev = 0.119
  CI (99.9%): [2.763, 7.096] (assumes normal distribution)


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
# Warmup Iteration   1: 12.882 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.018 ms/op
Iteration   1: 4.257 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.802 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   6.324 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  24.013 ms/op
                 createUser·p0.9999: 28.815 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   2: 4.194 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  15.877 ms/op
                 createUser·p0.9999: 28.439 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   3: 4.318 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   6.494 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  15.694 ms/op
                 createUser·p0.9999: 33.499 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 225505
  mean =      4.256 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 412 
    [ 2.500,  5.000) = 201342 
    [ 5.000,  7.500) = 18683 
    [ 7.500, 10.000) = 3887 
    [10.000, 12.500) = 670 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     19.496 ms/op
     p(99.9900) =     32.681 ms/op
     p(99.9990) =     35.094 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 12.778 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.747 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.445 ±(99.9%) 0.018 ms/op
Iteration   1: 4.285 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.872 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   6.480 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  22.413 ms/op
                 existUser·p0.9999: 27.444 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   2: 4.053 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  16.148 ms/op
                 existUser·p0.9999: 32.768 ms/op
                 existUser·p1.00:   33.948 ms/op

Iteration   3: 4.001 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   8.331 ms/op
                 existUser·p0.999:  27.722 ms/op
                 existUser·p0.9999: 31.261 ms/op
                 existUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 233637
  mean =      4.110 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 332 
    [ 2.500,  5.000) = 213821 
    [ 5.000,  7.500) = 14201 
    [ 7.500, 10.000) = 3953 
    [10.000, 12.500) = 763 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     22.413 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     33.628 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 13.317 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 4.645 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.017 ms/op
Iteration   1: 4.319 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  21.363 ms/op
                 getUser·p0.9999: 29.497 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   2: 4.152 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  25.989 ms/op
                 getUser·p0.9999: 28.279 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 4.225 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.976 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  15.980 ms/op
                 getUser·p0.9999: 31.932 ms/op
                 getUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226662
  mean =      4.231 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 138 
    [ 2.500,  5.000) = 206792 
    [ 5.000,  7.500) = 14870 
    [ 7.500, 10.000) = 3587 
    [10.000, 12.500) = 828 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     21.420 ms/op
     p(99.9900) =     31.053 ms/op
     p(99.9990) =     33.406 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 15.841 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.537 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.037 ±(99.9%) 0.020 ms/op
Iteration   1: 4.879 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  25.675 ms/op
                 listUser·p0.9999: 30.582 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 4.964 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  19.845 ms/op
                 listUser·p0.9999: 26.429 ms/op
                 listUser·p1.00:   29.426 ms/op

Iteration   3: 4.942 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.922 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 21.956 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194554
  mean =      4.928 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 144946 
    [ 5.000,  7.500) = 42332 
    [ 7.500, 10.000) = 5915 
    [10.000, 12.500) = 783 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     29.035 ms/op
     p(99.9990) =     31.171 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.492 ± 5.167  ops/ms
ClientPb.existUser                       thrpt       3   8.080 ± 5.107  ops/ms
ClientPb.getUser                         thrpt       3   7.669 ± 2.425  ops/ms
ClientPb.listUser                        thrpt       3   6.411 ± 3.407  ops/ms
ClientPb.createUser                       avgt       3   4.216 ± 2.200   ms/op
ClientPb.existUser                        avgt       3   3.898 ± 1.995   ms/op
ClientPb.getUser                          avgt       3   4.123 ± 1.184   ms/op
ClientPb.listUser                         avgt       3   4.929 ± 2.167   ms/op
ClientPb.createUser                     sample  225505   4.256 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.458           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.667           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.496           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.681           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  233637   4.110 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.806           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.847           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.413           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.687           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.948           ms/op
ClientPb.getUser                        sample  226662   4.231 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.890           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.716           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.420           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.053           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.522           ms/op
ClientPb.listUser                       sample  194554   4.928 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.190           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.570           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.644           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.035           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.326           ms/op
