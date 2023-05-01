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
# Warmup Iteration   1: 1.565 ops/ms
# Warmup Iteration   2: 3.493 ops/ms
# Warmup Iteration   3: 6.683 ops/ms
Iteration   1: 7.195 ops/ms
Iteration   2: 7.463 ops/ms
Iteration   3: 7.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.486 ±(99.9%) 5.533 ops/ms [Average]
  (min, avg, max) = (7.195, 7.486, 7.800), stdev = 0.303
  CI (99.9%): [1.954, 13.019] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.140 ops/ms
# Warmup Iteration   2: 5.767 ops/ms
# Warmup Iteration   3: 7.434 ops/ms
Iteration   1: 7.825 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 7.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.831 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (7.775, 7.831, 7.894), stdev = 0.060
  CI (99.9%): [6.743, 8.920] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 5.937 ops/ms
# Warmup Iteration   3: 7.081 ops/ms
Iteration   1: 7.953 ops/ms
Iteration   2: 7.879 ops/ms
Iteration   3: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.960 ±(99.9%) 1.545 ops/ms [Average]
  (min, avg, max) = (7.879, 7.960, 8.048), stdev = 0.085
  CI (99.9%): [6.415, 9.504] (assumes normal distribution)


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
# Warmup Iteration   1: 2.331 ops/ms
# Warmup Iteration   2: 5.477 ops/ms
# Warmup Iteration   3: 6.239 ops/ms
Iteration   1: 6.445 ops/ms
Iteration   2: 6.910 ops/ms
Iteration   3: 6.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.712 ±(99.9%) 4.376 ops/ms [Average]
  (min, avg, max) = (6.445, 6.712, 6.910), stdev = 0.240
  CI (99.9%): [2.336, 11.088] (assumes normal distribution)


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
# Warmup Iteration   1: 14.476 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.008 ms/op
Iteration   1: 4.217 ±(99.9%) 0.008 ms/op
Iteration   2: 4.102 ±(99.9%) 0.016 ms/op
Iteration   3: 4.204 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.174 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (4.102, 4.174, 4.217), stdev = 0.063
  CI (99.9%): [3.027, 5.322] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.684 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.004 ms/op
Iteration   1: 3.992 ±(99.9%) 0.010 ms/op
Iteration   2: 3.900 ±(99.9%) 0.008 ms/op
Iteration   3: 3.756 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.883 ±(99.9%) 2.168 ms/op [Average]
  (min, avg, max) = (3.756, 3.883, 3.992), stdev = 0.119
  CI (99.9%): [1.715, 6.051] (assumes normal distribution)


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
# Warmup Iteration   1: 14.240 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.898 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.008 ms/op
Iteration   1: 4.467 ±(99.9%) 0.007 ms/op
Iteration   2: 4.057 ±(99.9%) 0.013 ms/op
Iteration   3: 4.148 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.224 ±(99.9%) 3.932 ms/op [Average]
  (min, avg, max) = (4.057, 4.224, 4.467), stdev = 0.216
  CI (99.9%): [0.292, 8.156] (assumes normal distribution)


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
# Warmup Iteration   1: 15.817 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.734 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.034 ±(99.9%) 0.007 ms/op
Iteration   1: 4.681 ±(99.9%) 0.015 ms/op
Iteration   2: 4.967 ±(99.9%) 0.007 ms/op
Iteration   3: 4.812 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.820 ±(99.9%) 2.608 ms/op [Average]
  (min, avg, max) = (4.681, 4.820, 4.967), stdev = 0.143
  CI (99.9%): [2.212, 7.428] (assumes normal distribution)


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
# Warmup Iteration   1: 14.690 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.996 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.663 ±(99.9%) 0.022 ms/op
Iteration   1: 4.261 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   6.382 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 32.078 ms/op
                 createUser·p1.00:   33.128 ms/op

Iteration   2: 4.141 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  26.863 ms/op
                 createUser·p0.9999: 30.736 ms/op
                 createUser·p1.00:   31.326 ms/op

Iteration   3: 4.147 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.471 ms/op
                 createUser·p0.999:  12.744 ms/op
                 createUser·p0.9999: 33.554 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229492
  mean =      4.182 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 405 
    [ 2.500,  5.000) = 208325 
    [ 5.000,  7.500) = 17113 
    [ 7.500, 10.000) = 2799 
    [10.000, 12.500) = 555 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     20.988 ms/op
     p(99.9900) =     32.213 ms/op
     p(99.9990) =     33.843 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 14.544 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.013 ms/op
Iteration   1: 4.033 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.862 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.685 ms/op
                 existUser·p0.99:   8.118 ms/op
                 existUser·p0.999:  13.708 ms/op
                 existUser·p0.9999: 28.353 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 4.156 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   8.258 ms/op
                 existUser·p0.999:  27.332 ms/op
                 existUser·p0.9999: 30.101 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   3: 4.144 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.944 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  12.439 ms/op
                 existUser·p0.9999: 31.401 ms/op
                 existUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 233396
  mean =      4.110 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 292 
    [ 2.500,  5.000) = 213474 
    [ 5.000,  7.500) = 16454 
    [ 7.500, 10.000) = 2177 
    [10.000, 12.500) = 540 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 120 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     16.099 ms/op
     p(99.9900) =     30.463 ms/op
     p(99.9990) =     31.861 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 14.697 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.230 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.014 ms/op
Iteration   1: 4.324 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   7.111 ms/op
                 getUser·p0.99:   10.846 ms/op
                 getUser·p0.999:  25.002 ms/op
                 getUser·p0.9999: 27.066 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   2: 4.161 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   8.258 ms/op
                 getUser·p0.999:  19.366 ms/op
                 getUser·p0.9999: 27.666 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   3: 4.049 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   7.940 ms/op
                 getUser·p0.999:  27.526 ms/op
                 getUser·p0.9999: 30.062 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229847
  mean =      4.175 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 211124 
    [ 5.000,  7.500) = 13223 
    [ 7.500, 10.000) = 3653 
    [10.000, 12.500) = 1252 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 141 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     25.077 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     30.777 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 14.582 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 6.694 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.224 ±(99.9%) 0.022 ms/op
Iteration   1: 4.952 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   7.234 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  26.182 ms/op
                 listUser·p0.9999: 28.183 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 5.045 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.793 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 24.849 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   3: 5.117 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.642 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 190391
  mean =      5.037 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 128716 
    [ 5.000,  7.500) = 53710 
    [ 7.500, 10.000) = 6294 
    [10.000, 12.500) = 1065 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      2.454 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      7.070 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     21.293 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     28.429 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.486 ± 5.533  ops/ms
ClientPb.existUser                       thrpt       3   7.831 ± 1.088  ops/ms
ClientPb.getUser                         thrpt       3   7.960 ± 1.545  ops/ms
ClientPb.listUser                        thrpt       3   6.712 ± 4.376  ops/ms
ClientPb.createUser                       avgt       3   4.174 ± 1.147   ms/op
ClientPb.existUser                        avgt       3   3.883 ± 2.168   ms/op
ClientPb.getUser                          avgt       3   4.224 ± 3.932   ms/op
ClientPb.listUser                         avgt       3   4.820 ± 2.608   ms/op
ClientPb.createUser                     sample  229492   4.182 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.784           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.988           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.213           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  233396   4.110 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.565           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.995           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.099           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.463           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.096           ms/op
ClientPb.getUser                        sample  229847   4.175 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.306           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.077           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.524           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.031           ms/op
ClientPb.listUser                       sample  190391   5.037 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.454           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.748           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.293           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.558           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
