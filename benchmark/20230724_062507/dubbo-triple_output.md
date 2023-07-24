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
# Warmup Iteration   1: 1.529 ops/ms
# Warmup Iteration   2: 3.320 ops/ms
# Warmup Iteration   3: 6.997 ops/ms
Iteration   1: 7.666 ops/ms
Iteration   2: 8.122 ops/ms
Iteration   3: 7.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.923 ±(99.9%) 4.259 ops/ms [Average]
  (min, avg, max) = (7.666, 7.923, 8.122), stdev = 0.233
  CI (99.9%): [3.663, 12.182] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.129 ops/ms
# Warmup Iteration   2: 6.422 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 8.494 ops/ms
Iteration   2: 8.462 ops/ms
Iteration   3: 8.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.468 ±(99.9%) 0.422 ops/ms [Average]
  (min, avg, max) = (8.449, 8.468, 8.494), stdev = 0.023
  CI (99.9%): [8.046, 8.891] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.596 ops/ms
# Warmup Iteration   2: 6.306 ops/ms
# Warmup Iteration   3: 7.430 ops/ms
Iteration   1: 7.856 ops/ms
Iteration   2: 8.093 ops/ms
Iteration   3: 8.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.003 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (7.856, 8.003, 8.093), stdev = 0.129
  CI (99.9%): [5.654, 10.352] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.084 ops/ms
# Warmup Iteration   2: 5.920 ops/ms
# Warmup Iteration   3: 6.496 ops/ms
Iteration   1: 6.843 ops/ms
Iteration   2: 6.670 ops/ms
Iteration   3: 6.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.825 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (6.670, 6.825, 6.963), stdev = 0.148
  CI (99.9%): [4.132, 9.519] (assumes normal distribution)


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
# Warmup Iteration   1: 13.116 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.784 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.838 ±(99.9%) 0.016 ms/op
Iteration   2: 4.063 ±(99.9%) 0.010 ms/op
Iteration   3: 3.954 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.951 ±(99.9%) 2.056 ms/op [Average]
  (min, avg, max) = (3.838, 3.951, 4.063), stdev = 0.113
  CI (99.9%): [1.896, 6.007] (assumes normal distribution)


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
# Warmup Iteration   1: 12.833 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.008 ms/op
Iteration   1: 3.958 ±(99.9%) 0.009 ms/op
Iteration   2: 3.966 ±(99.9%) 0.005 ms/op
Iteration   3: 3.706 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.877 ±(99.9%) 2.695 ms/op [Average]
  (min, avg, max) = (3.706, 3.877, 3.966), stdev = 0.148
  CI (99.9%): [1.182, 6.571] (assumes normal distribution)


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
# Warmup Iteration   1: 13.744 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.993 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.946 ±(99.9%) 0.009 ms/op
Iteration   2: 3.894 ±(99.9%) 0.012 ms/op
Iteration   3: 3.905 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.915 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (3.894, 3.915, 3.946), stdev = 0.027
  CI (99.9%): [3.415, 4.416] (assumes normal distribution)


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
# Warmup Iteration   1: 14.894 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.336 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.917 ±(99.9%) 0.009 ms/op
Iteration   1: 4.614 ±(99.9%) 0.013 ms/op
Iteration   2: 4.708 ±(99.9%) 0.010 ms/op
Iteration   3: 4.640 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.654 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (4.614, 4.654, 4.708), stdev = 0.049
  CI (99.9%): [3.765, 5.543] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.339 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 5.770 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.621 ±(99.9%) 0.020 ms/op
Iteration   1: 4.127 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.847 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  23.415 ms/op
                 createUser·p0.9999: 27.165 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 4.116 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   7.335 ms/op
                 createUser·p0.999:  14.027 ms/op
                 createUser·p0.9999: 27.467 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 3.971 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  28.765 ms/op
                 createUser·p0.9999: 32.367 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235933
  mean =      4.070 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 154 
    [ 2.500,  5.000) = 219783 
    [ 5.000,  7.500) = 14017 
    [ 7.500, 10.000) = 1374 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     23.431 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     33.829 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 11.290 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.010 ms/op
Iteration   1: 3.832 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   7.057 ms/op
                 existUser·p0.999:  14.542 ms/op
                 existUser·p0.9999: 21.091 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 4.027 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.925 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   5.128 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   8.045 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 21.072 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   6.925 ms/op
                 existUser·p0.999:  22.142 ms/op
                 existUser·p0.9999: 25.059 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244187
  mean =      3.930 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 212 
    [ 2.500,  5.000) = 227809 
    [ 5.000,  7.500) = 13699 
    [ 7.500, 10.000) = 1768 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     15.693 ms/op
     p(99.9900) =     23.893 ms/op
     p(99.9990) =     25.905 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 13.225 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.012 ms/op
Iteration   1: 3.921 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.085 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  10.522 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   2: 4.020 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.101 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  24.819 ms/op
                 getUser·p0.9999: 41.288 ms/op
                 getUser·p1.00:   42.205 ms/op

Iteration   3: 3.901 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  24.993 ms/op
                 getUser·p0.9999: 27.910 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243264
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 233575 
    [ 5.000, 10.000) = 9173 
    [10.000, 15.000) = 260 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 80 
    [25.000, 30.000) = 144 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     23.191 ms/op
     p(99.9900) =     39.213 ms/op
     p(99.9990) =     41.915 ms/op
     p(99.9999) =     42.205 ms/op
    p(100.0000) =     42.205 ms/op


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
# Warmup Iteration   1: 14.370 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.709 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.951 ±(99.9%) 0.018 ms/op
Iteration   1: 4.624 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  24.539 ms/op
                 listUser·p0.9999: 27.468 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 4.755 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.719 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  19.357 ms/op
                 listUser·p0.9999: 21.767 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 4.669 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  18.069 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204950
  mean =      4.682 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 177654 
    [ 5.000,  7.500) = 23071 
    [ 7.500, 10.000) = 2966 
    [10.000, 12.500) = 664 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     20.121 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     27.715 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.923 ± 4.259  ops/ms
ClientPb.existUser                       thrpt       3   8.468 ± 0.422  ops/ms
ClientPb.getUser                         thrpt       3   8.003 ± 2.349  ops/ms
ClientPb.listUser                        thrpt       3   6.825 ± 2.693  ops/ms
ClientPb.createUser                       avgt       3   3.951 ± 2.056   ms/op
ClientPb.existUser                        avgt       3   3.877 ± 2.695   ms/op
ClientPb.getUser                          avgt       3   3.915 ± 0.501   ms/op
ClientPb.listUser                         avgt       3   4.654 ± 0.889   ms/op
ClientPb.createUser                     sample  235933   4.070 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.493           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.307           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.431           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.162           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  244187   3.930 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.151           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.512           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.693           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.893           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.985           ms/op
ClientPb.getUser                        sample  243264   3.947 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.085           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.809           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.191           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.213           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.205           ms/op
ClientPb.listUser                       sample  204950   4.682 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.109           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.121           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.640           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.853           ms/op
