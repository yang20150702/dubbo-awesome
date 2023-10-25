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
# Warmup Iteration   1: 1.680 ops/ms
# Warmup Iteration   2: 3.470 ops/ms
# Warmup Iteration   3: 7.259 ops/ms
Iteration   1: 7.319 ops/ms
Iteration   2: 7.579 ops/ms
Iteration   3: 7.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.628 ±(99.9%) 6.123 ops/ms [Average]
  (min, avg, max) = (7.319, 7.628, 7.985), stdev = 0.336
  CI (99.9%): [1.505, 13.751] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.204 ops/ms
# Warmup Iteration   2: 6.617 ops/ms
# Warmup Iteration   3: 7.923 ops/ms
Iteration   1: 8.075 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 7.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.059 ±(99.9%) 3.482 ops/ms [Average]
  (min, avg, max) = (7.860, 8.059, 8.241), stdev = 0.191
  CI (99.9%): [4.576, 11.541] (assumes normal distribution)


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
# Warmup Iteration   1: 2.239 ops/ms
# Warmup Iteration   2: 6.487 ops/ms
# Warmup Iteration   3: 7.606 ops/ms
Iteration   1: 7.947 ops/ms
Iteration   2: 7.676 ops/ms
Iteration   3: 7.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.684 ±(99.9%) 4.723 ops/ms [Average]
  (min, avg, max) = (7.429, 7.684, 7.947), stdev = 0.259
  CI (99.9%): [2.961, 12.407] (assumes normal distribution)


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
# Warmup Iteration   1: 2.110 ops/ms
# Warmup Iteration   2: 4.873 ops/ms
# Warmup Iteration   3: 6.411 ops/ms
Iteration   1: 6.520 ops/ms
Iteration   2: 6.758 ops/ms
Iteration   3: 6.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.692 ±(99.9%) 2.743 ops/ms [Average]
  (min, avg, max) = (6.520, 6.692, 6.799), stdev = 0.150
  CI (99.9%): [3.950, 9.435] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.000 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.448 ±(99.9%) 0.005 ms/op
Iteration   1: 4.185 ±(99.9%) 0.004 ms/op
Iteration   2: 4.176 ±(99.9%) 0.005 ms/op
Iteration   3: 4.100 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.154 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (4.100, 4.154, 4.185), stdev = 0.047
  CI (99.9%): [3.296, 5.011] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.894 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.005 ms/op
Iteration   1: 3.860 ±(99.9%) 0.004 ms/op
Iteration   2: 3.808 ±(99.9%) 0.007 ms/op
Iteration   3: 4.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.891 ±(99.9%) 1.869 ms/op [Average]
  (min, avg, max) = (3.808, 3.891, 4.006), stdev = 0.102
  CI (99.9%): [2.022, 5.761] (assumes normal distribution)


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
# Warmup Iteration   1: 13.614 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.722 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.003 ms/op
Iteration   1: 4.166 ±(99.9%) 0.002 ms/op
Iteration   2: 4.139 ±(99.9%) 0.004 ms/op
Iteration   3: 3.960 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.088 ±(99.9%) 2.044 ms/op [Average]
  (min, avg, max) = (3.960, 4.088, 4.166), stdev = 0.112
  CI (99.9%): [2.045, 6.132] (assumes normal distribution)


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
# Warmup Iteration   1: 15.524 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.502 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.933 ±(99.9%) 0.007 ms/op
Iteration   1: 4.899 ±(99.9%) 0.002 ms/op
Iteration   2: 5.036 ±(99.9%) 0.005 ms/op
Iteration   3: 4.867 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.934 ±(99.9%) 1.638 ms/op [Average]
  (min, avg, max) = (4.867, 4.934, 5.036), stdev = 0.090
  CI (99.9%): [3.297, 6.572] (assumes normal distribution)


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
# Warmup Iteration   1: 14.340 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.130 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.462 ±(99.9%) 0.018 ms/op
Iteration   1: 4.153 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.979 ms/op
                 createUser·p0.999:  22.968 ms/op
                 createUser·p0.9999: 26.650 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 4.196 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   8.194 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 27.787 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 3.992 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.923 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  27.754 ms/op
                 createUser·p0.9999: 31.850 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233377
  mean =      4.112 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 218364 
    [ 5.000,  7.500) = 12090 
    [ 7.500, 10.000) = 1919 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.888 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.710 ms/op
     p(99.9000) =     23.253 ms/op
     p(99.9900) =     30.529 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 13.579 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.011 ms/op
Iteration   1: 4.014 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.927 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  21.116 ms/op
                 existUser·p0.9999: 22.917 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   2: 3.898 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   8.004 ms/op
                 existUser·p0.999:  14.320 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   3: 4.059 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.847 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   7.717 ms/op
                 existUser·p0.999:  16.425 ms/op
                 existUser·p0.9999: 29.102 ms/op
                 existUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240378
  mean =      3.989 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 251 
    [ 2.500,  5.000) = 225710 
    [ 5.000,  7.500) = 12015 
    [ 7.500, 10.000) = 1728 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     16.394 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     29.386 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.005 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.942 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.379 ±(99.9%) 0.017 ms/op
Iteration   1: 4.333 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.327 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   7.012 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  16.663 ms/op
                 getUser·p0.9999: 25.810 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 4.131 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.979 ms/op
                 getUser·p0.999:  24.930 ms/op
                 getUser·p0.9999: 27.288 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 4.086 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   8.372 ms/op
                 getUser·p0.999:  16.450 ms/op
                 getUser·p0.9999: 30.802 ms/op
                 getUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229570
  mean =      4.181 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 212779 
    [ 5.000,  7.500) = 11565 
    [ 7.500, 10.000) = 3809 
    [10.000, 12.500) = 884 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     29.991 ms/op
     p(99.9990) =     30.956 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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
# Warmup Iteration   1: 13.909 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.494 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.034 ±(99.9%) 0.020 ms/op
Iteration   1: 4.947 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  24.478 ms/op
                 listUser·p0.9999: 29.085 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   2: 4.944 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  19.643 ms/op
                 listUser·p0.9999: 25.543 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   3: 4.921 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 19.020 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194636
  mean =      4.937 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 140235 
    [ 5.000,  7.500) = 48717 
    [ 7.500, 10.000) = 4133 
    [10.000, 12.500) = 873 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      9.480 ms/op
     p(99.9000) =     19.881 ms/op
     p(99.9900) =     26.416 ms/op
     p(99.9990) =     32.770 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.628 ± 6.123  ops/ms
ClientPb.existUser                       thrpt       3   8.059 ± 3.482  ops/ms
ClientPb.getUser                         thrpt       3   7.684 ± 4.723  ops/ms
ClientPb.listUser                        thrpt       3   6.692 ± 2.743  ops/ms
ClientPb.createUser                       avgt       3   4.154 ± 0.858   ms/op
ClientPb.existUser                        avgt       3   3.891 ± 1.869   ms/op
ClientPb.getUser                          avgt       3   4.088 ± 2.044   ms/op
ClientPb.listUser                         avgt       3   4.934 ± 1.638   ms/op
ClientPb.createUser                     sample  233377   4.112 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.888           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.253           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.529           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  240378   3.989 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.460           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.394           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.410           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.852           ms/op
ClientPb.getUser                        sample  229570   4.181 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.831           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.987           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.991           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.966           ms/op
ClientPb.listUser                       sample  194636   4.937 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.755           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.480           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.881           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.416           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.801           ms/op
