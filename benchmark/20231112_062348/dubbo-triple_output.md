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
# Warmup Iteration   1: 1.505 ops/ms
# Warmup Iteration   2: 3.630 ops/ms
# Warmup Iteration   3: 7.162 ops/ms
Iteration   1: 7.365 ops/ms
Iteration   2: 7.833 ops/ms
Iteration   3: 7.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.645 ±(99.9%) 4.502 ops/ms [Average]
  (min, avg, max) = (7.365, 7.645, 7.833), stdev = 0.247
  CI (99.9%): [3.143, 12.147] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.265 ops/ms
# Warmup Iteration   2: 6.310 ops/ms
# Warmup Iteration   3: 7.855 ops/ms
Iteration   1: 8.099 ops/ms
Iteration   2: 7.791 ops/ms
Iteration   3: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.001 ±(99.9%) 3.322 ops/ms [Average]
  (min, avg, max) = (7.791, 8.001, 8.113), stdev = 0.182
  CI (99.9%): [4.679, 11.323] (assumes normal distribution)


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
# Warmup Iteration   1: 2.152 ops/ms
# Warmup Iteration   2: 6.070 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 7.426 ops/ms
Iteration   2: 7.778 ops/ms
Iteration   3: 7.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.686 ±(99.9%) 4.169 ops/ms [Average]
  (min, avg, max) = (7.426, 7.686, 7.854), stdev = 0.228
  CI (99.9%): [3.518, 11.855] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.882 ops/ms
# Warmup Iteration   2: 5.386 ops/ms
# Warmup Iteration   3: 6.366 ops/ms
Iteration   1: 6.287 ops/ms
Iteration   2: 6.537 ops/ms
Iteration   3: 6.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.524 ±(99.9%) 4.220 ops/ms [Average]
  (min, avg, max) = (6.287, 6.524, 6.749), stdev = 0.231
  CI (99.9%): [2.305, 10.744] (assumes normal distribution)


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
# Warmup Iteration   1: 12.978 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.469 ±(99.9%) 0.008 ms/op
Iteration   1: 4.153 ±(99.9%) 0.008 ms/op
Iteration   2: 4.089 ±(99.9%) 0.005 ms/op
Iteration   3: 4.062 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.101 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (4.062, 4.101, 4.153), stdev = 0.047
  CI (99.9%): [3.243, 4.960] (assumes normal distribution)


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
# Warmup Iteration   1: 13.003 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.849 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.005 ms/op
Iteration   1: 3.932 ±(99.9%) 0.005 ms/op
Iteration   2: 3.894 ±(99.9%) 0.006 ms/op
Iteration   3: 3.939 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.922 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.894, 3.922, 3.939), stdev = 0.024
  CI (99.9%): [3.488, 4.355] (assumes normal distribution)


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
# Warmup Iteration   1: 14.182 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.901 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.411 ±(99.9%) 0.007 ms/op
Iteration   1: 4.045 ±(99.9%) 0.008 ms/op
Iteration   2: 4.153 ±(99.9%) 0.005 ms/op
Iteration   3: 4.080 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.093 ±(99.9%) 1.003 ms/op [Average]
  (min, avg, max) = (4.045, 4.093, 4.153), stdev = 0.055
  CI (99.9%): [3.089, 5.096] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.413 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.780 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.012 ±(99.9%) 0.008 ms/op
Iteration   1: 4.788 ±(99.9%) 0.008 ms/op
Iteration   2: 4.840 ±(99.9%) 0.008 ms/op
Iteration   3: 4.842 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.823 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (4.788, 4.823, 4.842), stdev = 0.031
  CI (99.9%): [4.265, 5.382] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.557 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.088 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.568 ±(99.9%) 0.020 ms/op
Iteration   1: 4.244 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.768 ms/op
                 createUser·p0.99:   8.200 ms/op
                 createUser·p0.999:  14.286 ms/op
                 createUser·p0.9999: 25.788 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   2: 4.035 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.847 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   7.807 ms/op
                 createUser·p0.999:  16.275 ms/op
                 createUser·p0.9999: 29.277 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   3: 4.120 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 30.883 ms/op
                 createUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232320
  mean =      4.131 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 296 
    [ 2.500,  5.000) = 213692 
    [ 5.000,  7.500) = 15653 
    [ 7.500, 10.000) = 1906 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     30.222 ms/op
     p(99.9990) =     32.245 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.533 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   8.497 ms/op
                 existUser·p0.999:  23.316 ms/op
                 existUser·p0.9999: 25.590 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 3.914 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   7.684 ms/op
                 existUser·p0.999:  13.163 ms/op
                 existUser·p0.9999: 26.962 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   3: 4.060 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  14.874 ms/op
                 existUser·p0.9999: 29.000 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240920
  mean =      3.982 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 279 
    [ 2.500,  5.000) = 226879 
    [ 5.000,  7.500) = 10151 
    [ 7.500, 10.000) = 2482 
    [10.000, 12.500) = 631 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     28.079 ms/op
     p(99.9990) =     29.710 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 14.390 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.015 ms/op
Iteration   1: 4.103 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  11.321 ms/op
                 getUser·p0.9999: 26.182 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   2: 4.236 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   6.210 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  25.688 ms/op
                 getUser·p0.9999: 28.162 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   3: 4.189 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  11.824 ms/op
                 getUser·p0.9999: 29.176 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229887
  mean =      4.175 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 212350 
    [ 5.000,  7.500) = 14720 
    [ 7.500, 10.000) = 2013 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     28.280 ms/op
     p(99.9990) =     29.744 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 15.762 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 5.865 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.995 ±(99.9%) 0.019 ms/op
Iteration   1: 4.904 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   9.465 ms/op
                 listUser·p0.999:  24.987 ms/op
                 listUser·p0.9999: 27.623 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   2: 4.963 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   7.242 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  22.269 ms/op
                 listUser·p0.9999: 30.248 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   3: 4.838 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  16.679 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195838
  mean =      4.901 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 147264 
    [ 5.000,  7.500) = 43132 
    [ 7.500, 10.000) = 4080 
    [10.000, 12.500) = 780 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.931 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     20.463 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     31.807 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.645 ± 4.502  ops/ms
ClientPb.existUser                       thrpt       3   8.001 ± 3.322  ops/ms
ClientPb.getUser                         thrpt       3   7.686 ± 4.169  ops/ms
ClientPb.listUser                        thrpt       3   6.524 ± 4.220  ops/ms
ClientPb.createUser                       avgt       3   4.101 ± 0.859   ms/op
ClientPb.existUser                        avgt       3   3.922 ± 0.434   ms/op
ClientPb.getUser                          avgt       3   4.093 ± 1.003   ms/op
ClientPb.listUser                         avgt       3   4.823 ± 0.559   ms/op
ClientPb.createUser                     sample  232320   4.131 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.096           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.774           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.423           ms/op
ClientPb.existUser                      sample  240920   3.982 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.610           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.487           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.991           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.900           ms/op
ClientPb.getUser                        sample  229887   4.175 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.521           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.766           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.512           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.280           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  195838   4.901 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.931           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.463           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.164           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.309           ms/op
